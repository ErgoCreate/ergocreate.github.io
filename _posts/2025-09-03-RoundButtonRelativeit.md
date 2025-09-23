---
layout: post

title:  "RoundButtonRelativeit"

categories: ["Api", "Widgets"]

tags: ['button', 'layout', 'layout constructor', 'relative', 'round']

---
`SimpleKivy.SimpleKivy.RoundButtonRelativeit(*widgets, k=None, enable_events=True, on_event='on_release', hover_highlight=False, focus_behavior=False, lcolor=[0.5, 0.5, 0.5, 1], bcolor_normal=[0.345, 0.345, 0.345, 0], bcolor_down=[0.2, 0.64, 0.8, 1], **kwargs)`{: .python}


![RoundButtonRelativeit.png](assets/img/docs/RoundButtonRelativeit.png){: width="286" height="75" }

![RoundButtonRelativeit.2.png](assets/img/docs/RoundButtonRelativeit.2.png){: width="286" height="37" }


Dynamic `RelativeLayout` constructor with ButtonBehavior and rounded corners for the border line and background color.

## Parameters


`*widgets: Widget`

> Positional arguments must be widgets and are added to the `RoundButtonRelativeit` instance as children during creation.

> Example:

```py
sk.RoundButtonRelativeit(sk.Label('a'), sk.Label('b'), sk.Label('c'), )
```



`bcolor, lcolor` and any other valid properties with ***color*** in their name can be specified with `sequence or str` during creation:

> - `sequence: [float, float, float, float]`: Sequence `(list or tuple)` of 4 `float` numbers (0.0-1.0). Same as `Kivy`.

> - `str: "{hex_string}"`: Hex color in the format `"#000000"`.

> - `str: "{named_color}"`: Name of a color from the [List of Named Colors](/posts/named_colors) supported by `SimpleKivy`.


>> `bcolor`: Background color of the widget.


>> `lcolor`: Line color of the widget.


`lwidth: number (float or int)`

> Width of the widget's border line.



`segments: int`

> Number of segments used to represent the rounded corners.

`r: VariableListProperty(length=4)`

> Radius used for each of the corners in the order `top-left, top-right, bottom-right, bottom-left`



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
sk.RoundButtonRelativeit(size = "y35")
sk.RoundButtonRelativeit(size = "x120y35")
sk.RoundButtonRelativeit(size = "xchildreny40")
sk.RoundButtonRelativeit(size = "xchildrenychildren")
sk.RoundButtonRelativeit(size = "xchild_maxy40")
sk.RoundButtonRelativeit(size = "60")
sk.RoundButtonRelativeit(size = (120,35), size_hint = (None, None))
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
sk.RoundButtonRelativeit(enable_events = True, on_event = 'width')
sk.RoundButtonRelativeit(enable_events = True, on_event = 'on_touch_down')
sk.RoundButtonRelativeit(enable_events = True, on_event = ['width','height','pos'])
sk.RoundButtonRelativeit(enable_events = True, on_event = {"size": lambda ins,v: print("size =",v)})

```

`do_dot_subevent: bool`

> Adds a "." to describe the event when triggering the event_manager.
> - `True`: The event identifier is `str(widget.id)+".{event_name}"`.

> - `False`: The event identifier is the same as the widget's `k/id`.

> Default is `False`.


## Returns

`RelativeLayout` created dynamically with `*widgets` added as children during creation.

## Kivy Bases

`RelativeLayout`


{: .prompt-info }

> This page only details the new or modified features. All other parameters inherit from the base Kivy widgets and can be found in the [official Kivy documentation](https://kivy.org/doc/stable).



## Properties

## Events


## When created with *hover_highlight = True*

### Properties


`tooltip_text (StringProperty)`: Tooltip to be displayed when the mouse hovers over the `RoundButtonRelativeit` widget. Default is `""`.

`tooltip_args (ObjectProperty)`: Dictionary of `Label` properties for the tooltip widget. See [Label](/posts/Label/). Default tooltip properties are `dict(color="#CCCCCC", bcolor=(.13,.13,.13,1), lcolor="gray", valign="middle", size="y30", size_behavior="texth", padding=[4,4,4,4])`.

`do_highlight (BooleanProperty)`: Whether the widget is highlighted when the mouse hovers over it. Default is `True`.



### Events


`on_enter()`: Fired when the mouse enters the widget.

`on_leave()`: Fired when the mouse leaves the widget.


