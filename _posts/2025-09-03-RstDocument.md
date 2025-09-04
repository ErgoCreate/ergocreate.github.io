---
layout: post

title:  "RstDocument"

categories: ["Api", "Widgets"]

tags: ['document', 'rst']

---
`SimpleKivy.SimpleKivy.RstDocument(text='', k=None, enable_events=True, do_dot_subevent=True, on_event='on_ref_press', **kwargs)`{: .python}


![RstDocument.png](assets/img/docs/RstDocument.png){: width="942" height="450" }


Creates a RstDocument widget dynamically with added functionalities.

Parameters
----------

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
RstDocument(size = "x120y35")
RstDocument(size = "xchildreny40")
RstDocument(size = "xchildrenychildren")
RstDocument(size = "xchild_maxy40")
RstDocument(size = "60")
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
RstDocument(enable_events = True, on_event = 'width')
RstDocument(enable_events = True, on_event = 'on_touch_down')
RstDocument(enable_events = True, on_event = ['width','height','pos'])
```

`do_dot_subevent: bool`

> Adds a "." to describe the event when triggering the event_manager
> - `True`: The event identifier is `str(widget.id)+".{event_name}"`

> - `False`: The event identifier is the same as the widget's `k/id`

> Default is False


Returns
-------
`RstDocument` widget created dynamically.

Kivy Bases
----------
`RstDocument`


{: .prompt-info }

> This page only details the new or modified features. All other parameters inherit from the base Kivy widgets and can be found in the [official Kivy documentation](https://kivy.org/doc/stable).

