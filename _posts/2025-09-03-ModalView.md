---
layout: post

title:  "ModalView"

categories: ["Api", "Widgets"]

tags: ['modal', 'view']

---
`SimpleKivy.SimpleKivy.ModalView(widgets=[], k=None, enable_events=False, on_event='on_pre_open', **kwargs)`{: .python}


Creates a ModalView widget dynamically with added functionalities.

Parameters
----------
`widgets: list, Widget`

> Widget instance or list of widgets to be added dynamically.
> - `Widget`: Adds the widget as child.

> - `[Widget, Widget, ...]`: Adds each Widget in the list as child.



`k: None, str, or NOTKEY`

> Key specification for quick acess:

> - `None`: Automatically sets an int value

> - `str`: Use specific string key

> - `NOTKEY`: Special flag indicating no key should be used, 

> Default is None.

`size: sequence of 2 ints or str`

> Size specification of the widget:


> **String formats**:

> - `"x{str: width}"`: Sets widget width and `size_hint_x = None`

> - `"y{str: height}"`: Sets widget height and `size_hint_y = None`

> - `"xchildren"`: Sets `size_hint_x = None` and binds this widget's width to the sum of the widths of its children.

> - `"ychildren"`: Sets `size_hint_y = None` and binds this widget's height to the sum of the heights of its children

> - `"xchild_max"`: Sets `size_hint_x = None` and binds this widget's width to the child with the maximum width.

> - `"ychild_max"`: Sets `size_hint_y = None` and binds this widget's height to the child with the maximum height.


{: .prompt-info }

> *You can combine up to two of the above size string specifications:*


> - `"{str: number}"`: Processed as `size = (number, number)` and `size_hint = (None,None)`. *Cannot be combined with other string specifications*.


> **Sequence format**:

> - `(width, height)`: Size of the widget. Same as kivy.


>> Example:

```py
ModalView(size = "x120y35")
ModalView(size = "xchildreny40")
ModalView(size = "xchildrenychildren")
ModalView(size = "xchild_maxy40")
ModalView(size = "60")
```

`enable_events: bool`

> Whether the widget will send events to the event_manager set in MyApp using the widgets `k/id` property as event identifier.
> - True: Triggers events.

> - False: Doesn't trigger events.


`on_event: str, iterable (tuple or list), dict`

> Defines which events/property changes will trigger the event_manager. Only has effect if `enable_events = True`
> - str: Name of the event or property that will trigger the event_manager.

> - tuple or list (str, str, ...): Will trigger events for each name in the iterable

> - dict: calls `widget.bind(**{on_event})` during widget creation


>> Example:

```py
ModalView(enable_events = True, on_event = 'width')
ModalView(enable_events = True, on_event = 'on_touch_down')
ModalView(enable_events = True, on_event = ['width','height','pos'])
```

`do_dot_subevent: bool`

> Adds a "." to describe the event when triggering the event_manager
> - `True`: The event identifier is `str(widget.id)+".{event_name}"`

> - `False`: The event identifier is the same as the widget's `k/id`

> Default is False


Returns
-------
`ModalView` widget created dynamically.

Kivy Bases
----------
`ModalView`
