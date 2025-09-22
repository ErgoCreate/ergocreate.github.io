---
layout: post
title:  "skWebView"
# categories: ["Example", "Info"]
---
A simple program to showcase the capabilities of the `WebView` widget in [SimpleKivy](https://ergocreate.github.io/simplekivy).

```py
import SimpleKivy.SimpleKivy as sk

layout=[
    [sk.Titlebar(size="y40")],
    [sk.In(k='url',hint_text='type an url address',size='y35',enable_events=True,on_event='on_text_validate')],
    [sk.BoxitH(
        sk.FlatRoundB('SimpleKivy',k='goto:https://ergocreate.github.io/simplekivy'),
        sk.FlatRoundB('ErgoCreate',k='goto:https://github.com/ErgoCreate'),
        sk.FlatRoundB('Google',k='goto:https://google.com'),
        sk.FlatRoundB('YouTube',k='goto:https://youtube.com'),
        size='y30',
        spacing=8
        )],
    [sk.WebView(k='web')]
]

def evman(app,ev):
    if ev=='url':
        new_url=app.ids.url.text
        if not new_url.startswith('http'):
            new_url='https://'+new_url
            app('url',text=new_url)
        app.ids.web.window.load_url(new_url)
    if ev[:5]=='goto:':
        app('url',text=ev[5:])
        app.trigger_event('url')

app=sk.MyApp(
    layout=layout,
    title='SKWeb',
    event_manager=evman,
    custom_titlebar=True,
    layout_args=dict(padding=8,spacing=8)
)
app.run()
```

![](/assets/img/examples/gallery/skWebView/github.png){: .normal width="150px" }
![](/assets/img/examples/gallery/skWebView/main.png){: .normal width="150px" }
![](/assets/img/examples/gallery/skWebView/video.png){: .normal width="150px" }
![](/assets/img/examples/gallery/skWebView/youtube.png){: .normal width="150px" }
