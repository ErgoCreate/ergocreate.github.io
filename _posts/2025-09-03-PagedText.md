---
layout: post

title:  "PagedText"

categories: ["Api", "Widgets"]

tags: ['label', 'paged', 'text']

---
`SimpleKivy.SimpleKivy.PagedText(pages=[], k=None, focus_behavior=False, halign='center', size_behavior='normal', valign='middle', **kwargs)`{: .python}


![PagedText.png](assets/img/docs/PagedText.png){: width="438" height="450" }

![PagedText.2.png](assets/img/docs/PagedText.2.png){: width="438" height="450" }


Creates a PagedText widget.

Dynamic Creation Parameters
---------------------------
`focus_behavior: bool`

> Whether the widget will have FocusBehavior:

> - `False`: No focus behavior

> - `True`: Widget class created with FocusBehavior

> Default is False.

Parameters
----------
`pages: list`

> A list where each element is a string representing each page
> - `[str, str, ...]`: List of page strings


`size_behavior: str`

> Defines special bindings for the behavior of text_size and size:

> - `"none"`: No binding between text_size and widget size

> - `"normal"`: Binds text_size to widget size

> - `"text"` or `"textv"`: This widgets's height will be set to the text content

> - `"texth"`: This widgets's width will be set to the text content

> Default is "normal"



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
PagedText(size = "x120y35")
PagedText(size = "xchildreny40")
PagedText(size = "xchildrenychildren")
PagedText(size = "xchild_maxy40")
PagedText(size = "60")
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
PagedText(enable_events = True, on_event = 'width')
PagedText(enable_events = True, on_event = 'on_touch_down')
PagedText(enable_events = True, on_event = ['width','height','pos'])
```

`do_dot_subevent: bool`

> Adds a "." to describe the event when triggering the event_manager
> - `True`: The event identifier is `str(widget.id)+".{event_name}"`

> - `False`: The event identifier is the same as the widget's `k/id`

> Default is False


Returns
-------
`Label` widget created dynamically with the following modifications:


Properties
----------
`page (NumericProperty)`: Page index. Defaults to `None`.

`pages (ListProperty)`: Initialized with the `pages` parameter. Defaults to `[]`.


Events
------
`on_page(ins,val)`: Fired when the current page index is changed.

`on_pages(ins,val)`: Fired when the value of pages is set.


Methods
-------
`reload()`: Sets page to 0 if pages is not empty.

`empty()`: Sets pages to [''] and clears current text.

`next_page()`: Goes to the next page.

`previous_page()`: Goes to the previous page.


Kivy Bases
----------
`Label`


{: .prompt-info }

> This page only details the new or modified features. All other parameters inherit from the base Kivy widgets and can be found in the [official Kivy documentation](https://kivy.org/doc/stable).

