---
layout: post

title:  "DatePicker"

categories: ["Api", "Widgets"]

tags: ['date', 'picker']

---
`SimpleKivy.SimpleKivy.DatePicker(k=None, year=2020, month=1, **kwargs)`{: .python}


![DatePicker.png](assets/img/docs/DatePicker.png){: width="240" height="225" }


Creates a DatePicker widget.

## Parameters

`year (int)`: Initial year. Defaults to `2020`.

`month (int)`: Initial month (1-12) -> (Jan-Dec). Defaults to `1`.


`size_behavior: str`

> Defines special bindings for the behavior of text_size and size:

> - `"none"`: No binding between text_size and widget size.

> - `"normal"`: Binds text_size to widget size.

> - `"text"` or `"textv"`: This widgets's height will be set to the text content.

> - `"texth"`: This widgets's width will be set to the text content.

> Default is "normal".



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
sk.DatePicker(size = "y35")
sk.DatePicker(size = "x120y35")
sk.DatePicker(size = "xchildreny40")
sk.DatePicker(size = "xchildrenychildren")
sk.DatePicker(size = "xchild_maxy40")
sk.DatePicker(size = "60")
sk.DatePicker(size = (120,35), size_hint = (None, None))
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
sk.DatePicker(enable_events = True, on_event = 'width')
sk.DatePicker(enable_events = True, on_event = 'on_touch_down')
sk.DatePicker(enable_events = True, on_event = ['width','height','pos'])
sk.DatePicker(enable_events = True, on_event = {"size": lambda ins,v: print("size =",v)})

```

`do_dot_subevent: bool`

> Adds a "." to describe the event when triggering the event_manager.
> - `True`: The event identifier is `str(widget.id)+".{event_name}"`.

> - `False`: The event identifier is the same as the widget's `k/id`.

> Default is `False`.


## Returns

`DatePicker` widget created dynamically.

## Properties

`picked (list)`: List of 3 strings `["{year}", "{month}", "{day}"]` containing the last date selected. Defaults to `["", "", ""]`.

`months (list)`: List of month names `["Jan", "Feb", "Mar", "Apr", "May", "Jun", "Jul", "Aug", "Sep", "Oct", "Nov", "Dec"]`.


## Kivy Bases

`BoxLayout`


{: .prompt-info }

> This page only details the new or modified features. All other parameters inherit from the base Kivy widgets and can be found in the [official Kivy documentation](https://kivy.org/doc/stable).



## Alias
- **Calendar**
- **DatePicker**
