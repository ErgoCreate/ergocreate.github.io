---

layout: post

title:  "Quickstart Tutorial"

categories: [Tutorials, Quickstart]

math: true
---
In this page, you'll find simple example programs for you to familiarized with *Simplekivy's* api and the standard *Codding Conventions*. Make sure to first [get started](/posts/getting-started).

## Codding Conventions

- `import SimpleKivy.SimpleKivy as sk`
- Name your app's main layout `lyt`.
- Make sure the `k` argument of your widgets (widget id) is of type `str`.
- Name your `event_manager` function `evman`.
- ... and name the first two positional arguments of your `event_manager` function `app` and `ev`:
```python
def evman(app,ev):
    pass
```
- Name your `MyApp` instance `app`:
```python
app = sk.MyApp(...)
```

## Why Do You Need Conventions?

- In this documentation you'll find example programs and tutorials that follow the same naming conventions for simplicity.
- Following the same naming conventions in your code will let you copy and paste the example code into your programs with minimal or no modifications needed.
- If you wish to share your code or help others, your code will be understandable for anyone familiar with `SimpleKivy`.

## Your First App

As your first app, lets just show a simple "Hello world" message.
![](assets/img/examples/hello_world.png){: width="500"}
```py
import SimpleKivy.SimpleKivy as sk

lyt=[
    [sk.T('Hello world')]
]

app = sk.MyApp(layout=lyt)
app.run()
```
## "Say hi!" App
Let's make something more complex to indroduce you to *Widget Sizing* and *Event Handling*. Let's make an app that greets the user by the name they input in a text box when they press a button.

![](assets/img/examples/say_hi.png){: width="500"}

```py
import SimpleKivy.SimpleKivy as sk

lyt=[
    [sk.BoxitH(
        sk.Input(hint_text='Enter your name',k='in'),
        sk.B('Say hi!',size='x80'),
        size='y30'
    )],
    [sk.T(k='msg')]
]

def evman(app,ev):
    if ev=='Say hi!':
        app('msg',text=f"Hi {app['in'].text}!")

app=sk.MyApp(
    layout=lyt,
    event_manager=evman
    )
app.run()
```
 > Widgets used [BoxitH](/posts/BoxitH), [TextInput](/posts/TextInput), [Button](/posts/Button)

## Widget "Maths"

Note that in the above program, a `BoxitH` widget was used to put a text input and a button in an horizontal box widget, so that both of them get interpreted as a single entity in the layout (which has size `(2 rows, 1 column)`), with the label being put in the second row.

To simplify encapsulation of widgets, all `SimpleKivy` widgets support two arithmetical operators:
- multiplication (`*`): Puts widgets next to each other horizontally, as if they were variables being multiplyed.
- division (`/`): Puts widgets below one another vertically, as if they were variables being divided.

In this context, the above layout can also be represented as $\frac{Input \cdot Button}{Label}$ in a `(1 row, 1 column)` layout:

```py
lyt=[
    [
        ( sk.Input(hint_text='Enter your name',size='y30',k='in')*sk.B('Say hi!',size='x80') )/
        sk.T(k='msg')
    ],
]
```

You only need to keep in mind that the horizontal `height` and `size_hint_y` gets set by the first widget being multiplied, and the `width` and `size_hint_x` of the vertical box gets set by the first widget being divided.
- `sk.Input(hint_text='Enter your name',size='y30',k='in')*sk.B('Say hi!',size='x80')`: Results in a `BoxitH` widget with `size = "y30"` (or `height=30, size_hint_y=None`)
- The abve `BoxitH` is then divided by `sk.T(k='msg')`, resulting in a `BoxitV` widget that doesn't set the `width`, so `size_hint_x = 1` is used by default.

The use of *Widget Maths* is optional. It is just a helpful feature to have for simple combination of widgets in boxes.

## Widget Events
All widgets, which have events enabled during creation, will trigger a callback to the *Event Manager* (set by the `event_manager` argument in the `MyApp` class). This event manager can be:
- A single function
- ... or multiple functions decorated by methods of an instance of `SimpleKivy.EventManager` (see [EventManager](/posts/EventManager))

In any case, the function(s) must accept at least the two positional arguments `app` and `ev`, which are the current `SimpleKivy.MyApp` instance and the `event` (ID of the widget) that was triggered. See [SimpleKivy.MyApp](/posts/MyApp)

Below is an example code for a program that captures all events and shows them in the screen in a `Label` widget with id `"msg"`, alongside a count of all the events so far.
![](assets/img/examples/catch_events.png){: width="500"}
```py
import SimpleKivy.SimpleKivy as sk

lyt=[
    [sk.B('btn1'),sk.B('btn2')],
    [sk.Input(hint_text="try typing",k='in', enable_events=True, on_event='text'), sk.Spinner2(enable_events=True,k='spinner')],
    [sk.CheckBox(active=True,k='cb', enable_events=True), sk.Switch(k='switch',enable_events=True)],
    [sk.T("Last event:", halign='right',padding=4),sk.T(k='msg')],
]

count=0
def evman(app,ev):
    global count
    app('msg', text=f'"{ev}", {count = }')
    count+=1

app=sk.MyApp(
    layout=lyt,
    event_manager=evman
    )
app.run()
```

Inside the event manager, you can perform actions based on the value of the `ev` argument. For that, you can create `if` or `match-case` structures.

```py
# "if" structure
def evman(app, ev):
    if ev=="btn1":
        # do something
        pass
    elif ev=="btn2":
        # do something
        pass
    elif ev=="in":
        # do something
        pass
    elif ev in ("cb","switch"):
        # do something
        pass
```
```py
# match-case structure
def evman(app, ev):
    match(ev):
        case 'btn1':
            # do something
            pass
        case 'btn2':
            # do something
            pass
        case 'in':
            # do something
            pass
```

## Widget lookup.
When your *app* is **already running**, you can look up widgets by their ID, which is set by the `k` argument of `SimpleKivy` widgets.

For example, if you define a label widget with `sk.Label("hello world", k="lbl")`, you can get a reference to it by:
#### Through an instance of *MyApp*
- `app["lbl"]`: The recomended method. With `app` being an instance of `MyApp` (the same as the first argument of the `event_manager`).
- `app.ids["lbl"]`: Same as the above.
- `app.ids.lbl`: When the *widget ID* adheres to variable naming conventions, you can access the widget by the `ids` atribute of an instance of `MyApp` using *dot notation*.

#### Through *sk.ids*
- `sk.ids["lbl"]`: Similar to the above, but you can access the widget by the `ids` atribute of the `SimpleKivy.SimpleKivy` submodule. The difference is that when the `k` argument is not explicitly set, a reference is not kept in the `sk.ids` attribute.
- `sk.ids.lbl`: Similar to the above, but the *widget ID* must adhere to variable naming conventions to find it using *dot notation*.

## Changing widget properties
When you already have a reference to a widget and you want to modify its properties, for example changing the text of a label or the source of an image, it can be done as easily as:
```py
def evman(app,ev):
    ...
    app["lbl"].text = "New text"
    ...
```

However, if you are managing multithreading tasks, you might get an error similar to `"Cannot create graphics instruction outside the main Kivy thread"`, in which case, any property that modifies visual elements in your *UI* will trigger errors. To solve this, the recommended solution is to schedule your property changes.

`SimpleKivy` offers an *intituive foolproof* way to make sure your property updates are always scheduled in the *main kivy thread* as soon as possible.
```py
def evman(app,ev):
    ...
    app("lbl",text = "New text") # Foolproof property update
    # You can also schedule property updates for multiple properties
    # app("lbl", text = "New text", halign = "right", color = "red")
    ...
```

This method allows you to schedule property updates that won't cause errors when trying tasks in the main thread or in other threads.

There are other ways to achieve this. For more information see the `schedule_...` methods in the [class documentation of sk.MyApp](/posts/MyApp).