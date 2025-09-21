---
layout: post

title:  "LabelCheck"

categories: ["Api", "Widgets"]

tags: ['check', 'label']

---
`SimpleKivy.SimpleKivy.LabelCheck(text='checkbox', halign='left', valign='middle', enable_events=False, on_event='active', cwidth=40, active=False, k=None, **kwargs)`{: .python}


![LabelCheck.png](assets/img/docs/LabelCheck.png){: width="193" height="75" }

![LabelCheck.2.png](assets/img/docs/LabelCheck.2.png){: width="215" height="136" }


Creates a LabelCheck widget dynamically with added functionalities.

## Parameters

`text (str)`: Text value shown when created. Default is `"checkbox"`.


`halign (str)`: Horizontal text alignment. It can be one of `"left", "center", "right"`. Default is `"left"`.


`valign (str)`: Vertical text alignment. It can be one of `"top", "middle", "bottom"`. Default is `"middle"`.


`active (bool)`: Checkbox state. Default is `False`.


`cwidth (int)`: Width of the checkbox. Default is `40`



`k: None, str, or NOTKEY`

> Key specification for quick acess:

> - `None`: Automatically sets an int value.

> - `str`: Use specific string key.

> - `NOTKEY`: Special flag indicating no key should be used.


`size: str or sequence of 2 ints`

> Size specification of the widget:


> - `str: "x{width}"`: Sets widget `width` and `size_hint_x = None`.

> - `str: "y{height}"`: Sets widget `height` and `size_hint_y = None`.

> - `str: "xchildren"`: Sets `size_hint_x = None` and binds this widget's width to the sum of the widths of its children.

> - `str: "ychildren"`: Sets `size_hint_y = None` and binds this widget's height to the sum of the heights of its children.

> - `str: "xchild_max"`: Sets `size_hint_x = None` and binds this widget's width to the child with the maximum width.

> - `str: "ychild_max"`: Sets `size_hint_y = None` and binds this widget's height to the child with the maximum height.


{: .prompt-info }

> *You can combine up to two of the above size string specifications.*

> - `str: "{number}"`: Processed as `size = (number, number)` and `size_hint = (None,None)`. *Cannot be combined with other string specifications*.


> - `sequence: (int, int)`: Size of the widget. Same as `Kivy`. Has no effect if `size_hint` argument is not set to `None`.


> Example:

```py
sk.LabelCheck(size = "y35")
sk.LabelCheck(size = "x120y35")
sk.LabelCheck(size = "xchildreny40")
sk.LabelCheck(size = "xchildrenychildren")
sk.LabelCheck(size = "xchild_maxy40")
sk.LabelCheck(size = "60")
sk.LabelCheck(size = (120,35), size_hint = (None, None))
```

`enable_events: bool`

> Whether the widget will send events to the event_manager set in MyApp using the widgets `k/id` property as event identifier.
> - `True`: Triggers events.

> - `False`: Doesn't trigger events.


`on_event: str, iterable (tuple or list), dict`

> Defines which events/property changes will trigger the event_manager. Only has effect if `enable_events = True`.
> - `str`: Name of the event or property that will trigger the event_manager.

> - `iterable: [str, str, ...]`: Will trigger events for each name in the iterable.

> - `dict: {"{event_name}": callback}`: Calls `instance.bind(**on_event)` during widget creation.


> Example:

```py
sk.LabelCheck(enable_events = True, on_event = 'width')
sk.LabelCheck(enable_events = True, on_event = 'on_touch_down')
sk.LabelCheck(enable_events = True, on_event = ['width','height','pos'])
sk.LabelCheck(enable_events = True, on_event = {"size": lambda ins,v: print("size =",v)})

```

`do_dot_subevent: bool`

> Adds a "." to describe the event when triggering the event_manager.
> - `True`: The event identifier is `str(widget.id)+".{event_name}"`.

> - `False`: The event identifier is the same as the widget's `k/id`.

> Default is `False`.


## Returns

`LabelCheck` widget created dynamically.

## Kivy Bases

`BoxLayout, Label, CheckBox`


{: .prompt-info }

> This page only details the new or modified features. All other parameters inherit from the base Kivy widgets and can be found in the [official Kivy documentation](https://kivy.org/doc/stable).

