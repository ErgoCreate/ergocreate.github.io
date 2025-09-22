---
layout: post

title:  "EventManager"

categories: ["Api", "Classes"]

tags: ['event', 'manager']

---
`SimpleKivy.SimpleKivy.EventManager()`{: .python}


The EventManager class is an alternative to handling SimpleKivy events.

It provides different types of decorator methods to define rules for catching events.
Optimized for speed in applications with a huge amount of different events.

## Decorator Methods
`@EventManager.start`: Sets the callback for the `"__Start__"`) event.

`@EventManager.close`: Sets the callback for the `"__Close__"`) event.

`@EventManager.event() or @EventManager.event( event_name = str )`: Sets a callback for an **exact match** (`==`) corresponding to an event id. Accepts an `event_name` argument, which let's you set the catch rule `event == event_name`. `event_name` defaults to None, in which case the function name is used as the `event_name` value.

`@EventManager.rule( rule_callback = function )`: Sets a callback for any event that meets a custom rule function. Needs the positional argument `rule_callback`, which has to be a function that accepts **one** argument, and returns a value that can be converted to `bool`, for example: `True, False, None, "hello", "", 0, 1`. Rule testing is only performed once. If the `bool` conversion returns `True` by the `rule_callback`, the event is cached to immediately trigger the callback decorated with `rule` when triggering the same event id again.


`@EventManager.unhandled`: Sets a callback for any event that is not caught by any other rule.


Exact matches (set by the `event` decorator) are always tested first before `rule` decorator testing.

> Example:


```py
evman=sk.EventManager()

@evman.event("btn")
def on_btn(app,ev):
    """Handles the "btn" event"""

@evman.event()
def Exit(app,ev):
    """Handles the "Exit" event"""

@evman.start
def on_start(app,ev):
    """Handles the "__Start__" event"""

@evman.close
def on_start(app,ev):
    """Handles the "__Close__" event"""

@evman.rule(lambda x: x.startswith('http'))
def on_http(app,ev):
    """"Will catch any event that starts with "http"."""

@evman.unhandled
def on_other(app,ev):
    """Handles any other events that are not caught by an exact match or rule."""

app = sk.MyApp(
    ...
    event_manager = evman,
    ...
)
```
