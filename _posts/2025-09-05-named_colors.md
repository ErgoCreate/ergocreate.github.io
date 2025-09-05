---
layout: post

title:  "Named Colors"

categories: ["Tutorials", "Colors","Named"]

tags: ['colors']

---


Below is the comple list of all named colors supported by `SimpleKivy`, based in `matplotlib`'s [list of named colors](https://matplotlib.org/stable/gallery/color/named_colors), with the addition of colors `""` and `"transparent"`, that set the color to `[0,0,0,0]`.
They can be used during creation for ***any*** property that includes the word ***"color"*** in its name, and after creation for *almost* every custom `SimpleKivy` widget.

- Example
```python
sk.Button("button", background_color = "xkcd:marine")
sk.Label("label", bcolor = "tab:blue", lcolor = "k", color="xkcd:almost black")
sk.FlatRoundButton("button", bcolor_normal="",lcolor="k")
```

## CSS4/X11
-----------
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="transparent" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"b" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#0000ff" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"g" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#007f00" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"r" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ff0000" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"c" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#00bfbf" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"m" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#bf00bf" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"y" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#bfbf00" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"k" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#000000" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"w" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ffffff" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"aliceblue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#f0f8ff" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"antiquewhite" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#faebd7" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"aqua" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#00ffff" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"aquamarine" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#7fffd4" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"azure" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#f0ffff" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"beige" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#f5f5dc" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"bisque" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ffe4c4" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"black" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#000000" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"blanchedalmond" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ffebcd" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#0000ff" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"blueviolet" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#8a2be2" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"brown" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#a52a2a" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"burlywood" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#deb887" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"cadetblue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#5f9ea0" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"chartreuse" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#7fff00" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"chocolate" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#d2691e" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"coral" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ff7f50" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"cornflowerblue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#6495ed" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"cornsilk" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fff8dc" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"crimson" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#dc143c" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"cyan" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#00ffff" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"darkblue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#00008b" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"darkcyan" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#008b8b" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"darkgoldenrod" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#b8860b" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"darkgray" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#a9a9a9" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"darkgreen" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#006400" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"darkgrey" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#a9a9a9" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"darkkhaki" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#bdb76b" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"darkmagenta" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#8b008b" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"darkolivegreen" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#556b2f" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"darkorange" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ff8c00" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"darkorchid" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#9932cc" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"darkred" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#8b0000" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"darksalmon" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#e9967a" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"darkseagreen" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#8fbc8f" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"darkslateblue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#483d8b" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"darkslategray" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#2f4f4f" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"darkslategrey" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#2f4f4f" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"darkturquoise" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#00ced1" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"darkviolet" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#9400d3" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"deeppink" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ff1493" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"deepskyblue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#00bfff" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"dimgray" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#696969" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"dimgrey" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#696969" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"dodgerblue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#1e90ff" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"firebrick" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#b22222" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"floralwhite" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fffaf0" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"forestgreen" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#228b22" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"fuchsia" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ff00ff" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"gainsboro" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#dcdcdc" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"ghostwhite" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#f8f8ff" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"gold" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ffd700" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"goldenrod" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#daa520" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"gray" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#808080" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#008000" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"greenyellow" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#adff2f" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"grey" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#808080" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"honeydew" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#f0fff0" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"hotpink" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ff69b4" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"indianred" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#cd5c5c" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"indigo" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#4b0082" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"ivory" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fffff0" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"khaki" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#f0e68c" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"lavender" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#e6e6fa" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"lavenderblush" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fff0f5" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"lawngreen" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#7cfc00" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"lemonchiffon" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fffacd" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"lightblue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#add8e6" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"lightcoral" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#f08080" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"lightcyan" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#e0ffff" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"lightgoldenrodyellow" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fafad2" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"lightgray" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#d3d3d3" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"lightgreen" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#90ee90" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"lightgrey" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#d3d3d3" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"lightpink" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ffb6c1" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"lightsalmon" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ffa07a" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"lightseagreen" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#20b2aa" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"lightskyblue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#87cefa" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"lightslategray" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#778899" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"lightslategrey" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#778899" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"lightsteelblue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#b0c4de" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"lightyellow" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ffffe0" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"lime" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#00ff00" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"limegreen" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#32cd32" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"linen" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#faf0e6" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"magenta" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ff00ff" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"maroon" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#800000" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"mediumaquamarine" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#66cdaa" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"mediumblue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#0000cd" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"mediumorchid" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ba55d3" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"mediumpurple" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#9370db" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"mediumseagreen" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#3cb371" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"mediumslateblue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#7b68ee" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"mediumspringgreen" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#00fa9a" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"mediumturquoise" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#48d1cc" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"mediumvioletred" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#c71585" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"midnightblue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#191970" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"mintcream" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#f5fffa" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"mistyrose" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ffe4e1" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"moccasin" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ffe4b5" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"navajowhite" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ffdead" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"navy" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#000080" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"oldlace" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fdf5e6" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"olive" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#808000" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"olivedrab" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#6b8e23" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"orange" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ffa500" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"orangered" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ff4500" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"orchid" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#da70d6" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"palegoldenrod" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#eee8aa" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"palegreen" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#98fb98" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"paleturquoise" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#afeeee" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"palevioletred" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#db7093" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"papayawhip" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ffefd5" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"peachpuff" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ffdab9" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"peru" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#cd853f" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"pink" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ffc0cb" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"plum" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#dda0dd" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"powderblue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#b0e0e6" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"purple" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#800080" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"rebeccapurple" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#663399" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"red" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ff0000" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"rosybrown" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#bc8f8f" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"royalblue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#4169e1" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"saddlebrown" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#8b4513" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"salmon" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fa8072" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"sandybrown" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#f4a460" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"seagreen" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#2e8b57" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"seashell" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fff5ee" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"sienna" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#a0522d" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"silver" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#c0c0c0" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"skyblue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#87ceeb" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"slateblue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#6a5acd" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"slategray" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#708090" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"slategrey" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#708090" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"snow" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fffafa" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"springgreen" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#00ff7f" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"steelblue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#4682b4" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"tan" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#d2b48c" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"teal" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#008080" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"thistle" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#d8bfd8" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"tomato" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ff6347" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"turquoise" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#40e0d0" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"violet" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ee82ee" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"wheat" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#f5deb3" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"white" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ffffff" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"whitesmoke" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#f5f5f5" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"yellow" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ffff00" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"yellowgreen" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#9acd32" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"transparent" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="transparent" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;

## Tableu
---------
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"tab:blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#1f77b4" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"tab:orange" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ff7f0e" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"tab:green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#2ca02c" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"tab:red" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#d62728" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"tab:purple" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#9467bd" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"tab:brown" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#8c564b" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"tab:pink" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#e377c2" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"tab:gray" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#7f7f7f" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"tab:olive" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#bcbd22" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"tab:cyan" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#17becf" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"tab:grey" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#7f7f7f" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
## XKCD
-------
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:cloudy blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#acc2d9" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dark pastel green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#56ae57" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dust" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#b2996e" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:electric lime" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#a8ff04" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:fresh green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#69d84f" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light eggplant" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#894585" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:nasty green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#70b23f" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:really light blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#d4ffff" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:tea" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#65ab7c" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:warm purple" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#952e8f" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:yellowish tan" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fcfc81" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:cement" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#a5a391" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dark grass green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#388004" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dusty teal" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#4c9085" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:grey teal" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#5e9b8a" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:macaroni and cheese" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#efb435" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:pinkish tan" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#d99b82" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:spruce" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#0a5f38" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:strong blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#0c06f7" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:toxic green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#61de2a" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:windows blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#3778bf" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:blue blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#2242c7" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:blue with a hint of purple" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#533cc6" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:booger" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#9bb53c" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:bright sea green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#05ffa6" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dark green blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#1f6357" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:deep turquoise" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#017374" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:green teal" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#0cb577" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:strong pink" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ff0789" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:bland" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#afa88b" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:deep aqua" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#08787f" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:lavender pink" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#dd85d7" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light moss green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#a6c875" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light seafoam green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#a7ffb5" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:olive yellow" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#c2b709" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:pig pink" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#e78ea5" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:deep lilac" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#966ebd" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:desert" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ccad60" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dusty lavender" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ac86a8" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:purpley grey" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#947e94" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:purply" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#983fb2" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:candy pink" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ff63e9" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light pastel green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#b2fba5" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:boring green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#63b365" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:kiwi green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#8ee53f" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light grey green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#b7e1a1" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:orange pink" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ff6f52" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:tea green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#bdf8a3" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:very light brown" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#d3b683" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:egg shell" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fffcc4" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:eggplant purple" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#430541" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:powder pink" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ffb2d0" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:reddish grey" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#997570" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:baby shit brown" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ad900d" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:liliac" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#c48efd" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:stormy blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#507b9c" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:ugly brown" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#7d7103" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:custard" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fffd78" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:darkish pink" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#da467d" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:deep brown" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#410200" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:greenish beige" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#c9d179" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:manilla" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fffa86" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:off blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#5684ae" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:battleship grey" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#6b7c85" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:browny green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#6f6c0a" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:bruise" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#7e4071" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:kelley green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#009337" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:sickly yellow" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#d0e429" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:sunny yellow" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fff917" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:azul" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#1d5dec" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:darkgreen" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#054907" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:green/yellow" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#b5ce08" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:lichen" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#8fb67b" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light light green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#c8ffb0" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:pale gold" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fdde6c" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:sun yellow" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ffdf22" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:tan green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#a9be70" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:burple" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#6832e3" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:butterscotch" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fdb147" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:toupe" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#c7ac7d" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dark cream" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fff39a" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:indian red" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#850e04" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light lavendar" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#efc0fe" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:poison green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#40fd14" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:baby puke green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#b6c406" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:bright yellow green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#9dff00" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:charcoal grey" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#3c4142" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:squash" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#f2ab15" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:cinnamon" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ac4f06" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light pea green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#c4fe82" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:radioactive green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#2cfa1f" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:raw sienna" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#9a6200" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:baby purple" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ca9bf7" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:cocoa" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#875f42" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light royal blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#3a2efe" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:orangeish" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fd8d49" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:rust brown" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#8b3103" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:sand brown" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#cba560" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:swamp" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#698339" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:tealish green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#0cdc73" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:burnt siena" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#b75203" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:camo" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#7f8f4e" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dusk blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#26538d" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:fern" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#63a950" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:old rose" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#c87f89" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:pale light green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#b1fc99" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:peachy pink" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ff9a8a" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:rosy pink" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#f6688e" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light bluish green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#76fda8" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light bright green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#53fe5c" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light neon green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#4efd54" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light seafoam" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#a0febf" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:tiffany blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#7bf2da" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:washed out green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#bcf5a6" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:browny orange" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ca6b02" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:nice blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#107ab0" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:sapphire" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#2138ab" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:greyish teal" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#719f91" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:orangey yellow" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fdb915" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:parchment" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fefcaf" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:straw" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fcf679" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:very dark brown" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#1d0200" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:terracota" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#cb6843" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:ugly blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#31668a" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:clear blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#247afd" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:creme" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ffffb6" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:foam green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#90fda9" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:grey/green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#86a17d" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light gold" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fddc5c" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:seafoam blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#78d1b6" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:topaz" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#13bbaf" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:violet pink" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fb5ffc" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:wintergreen" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#20f986" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:yellow tan" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ffe36e" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dark fuchsia" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#9d0759" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:indigo blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#3a18b1" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light yellowish green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#c2ff89" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:pale magenta" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#d767ad" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:rich purple" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#720058" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:sunflower yellow" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ffda03" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:green/blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#01c08d" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:leather" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ac7434" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:racing green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#014600" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:vivid purple" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#9900fa" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dark royal blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#02066f" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:hazel" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#8e7618" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:muted pink" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#d1768f" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:booger green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#96b403" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:canary" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fdff63" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:cool grey" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#95a3a6" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dark taupe" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#7f684e" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:darkish purple" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#751973" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:true green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#089404" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:coral pink" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ff6163" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dark sage" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#598556" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dark slate blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#214761" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:flat blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#3c73a8" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:mushroom" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ba9e88" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:rich blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#021bf9" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dirty purple" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#734a65" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:greenblue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#23c48b" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:icky green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#8fae22" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light khaki" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#e6f2a2" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:warm blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#4b57db" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dark hot pink" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#d90166" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:deep sea blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#015482" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:carmine" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#9d0216" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dark yellow green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#728f02" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:pale peach" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ffe5ad" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:plum purple" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#4e0550" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:golden rod" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#f9bc08" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:neon red" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ff073a" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:old pink" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#c77986" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:very pale blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#d6fffe" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:blood orange" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fe4b03" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:grapefruit" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fd5956" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:sand yellow" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fce166" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:clay brown" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#b2713d" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dark blue grey" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#1f3b4d" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:flat green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#699d4c" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light green blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#56fca2" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:warm pink" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fb5581" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dodger blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#3e82fc" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:gross green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#a0bf16" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:ice" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#d6fffa" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:metallic blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#4f738e" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:pale salmon" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ffb19a" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:sap green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#5c8b15" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:algae" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#54ac68" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:bluey grey" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#89a0b0" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:greeny grey" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#7ea07a" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:highlighter green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#1bfc06" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light light blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#cafffb" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light mint" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#b6ffbb" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:raw umber" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#a75e09" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:vivid blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#152eff" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:deep lavender" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#8d5eb7" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dull teal" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#5f9e8f" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light greenish blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#63f7b4" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:mud green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#606602" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:pinky" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fc86aa" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:red wine" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#8c0034" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:shit green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#758000" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:tan brown" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ab7e4c" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:darkblue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#030764" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:rosa" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fe86a4" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:lipstick" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#d5174e" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:pale mauve" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fed0fc" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:claret" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#680018" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dandelion" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fedf08" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:orangered" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fe420f" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:poop green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#6f7c00" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:ruby" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ca0147" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dark" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#1b2431" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:greenish turquoise" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#00fbb0" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:pastel red" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#db5856" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:piss yellow" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ddd618" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:bright cyan" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#41fdfe" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dark coral" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#cf524e" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:algae green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#21c36f" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:darkish red" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#a90308" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:reddy brown" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#6e1005" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:blush pink" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fe828c" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:camouflage green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#4b6113" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:lawn green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#4da409" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:putty" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#beae8a" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:vibrant blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#0339f8" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dark sand" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#a88f59" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:purple/blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#5d21d0" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:saffron" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#feb209" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:twilight" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#4e518b" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:warm brown" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#964e02" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:bluegrey" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#85a3b2" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:bubble gum pink" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ff69af" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:duck egg blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#c3fbf4" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:greenish cyan" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#2afeb7" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:petrol" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#005f6a" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:royal" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#0c1793" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:butter" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ffff81" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dusty orange" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#f0833a" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:off yellow" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#f1f33f" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:pale olive green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#b1d27b" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:orangish" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fc824a" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:leaf" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#71aa34" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light blue grey" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#b7c9e2" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dried blood" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#4b0101" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:lightish purple" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#a552e6" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:rusty red" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#af2f0d" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:lavender blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#8b88f8" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light grass green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#9af764" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light mint green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#a6fbb2" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:sunflower" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ffc512" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:velvet" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#750851" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:brick orange" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#c14a09" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:lightish red" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fe2f4a" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:pure blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#0203e2" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:twilight blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#0a437a" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:violet red" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#a50055" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:yellowy brown" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ae8b0c" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:carnation" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fd798f" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:muddy yellow" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#bfac05" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dark seafoam green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#3eaf76" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:deep rose" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#c74767" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dusty red" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#b9484e" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:grey/blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#647d8e" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:lemon lime" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#bffe28" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:purple/pink" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#d725de" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:brown yellow" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#b29705" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:purple brown" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#673a3f" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:wisteria" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#a87dc2" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:banana yellow" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fafe4b" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:lipstick red" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#c0022f" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:water blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#0e87cc" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:brown grey" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#8d8468" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:vibrant purple" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ad03de" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:baby green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#8cff9e" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:barf green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#94ac02" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:eggshell blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#c4fff7" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:sandy yellow" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fdee73" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:cool green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#33b864" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:pale" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fff9d0" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:blue/grey" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#758da3" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:hot magenta" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#f504c9" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:greyblue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#77a1b5" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:purpley" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#8756e4" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:baby shit green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#889717" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:brownish pink" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#c27e79" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dark aquamarine" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#017371" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:diarrhea" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#9f8303" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light mustard" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#f7d560" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:pale sky blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#bdf6fe" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:turtle green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#75b84f" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:bright olive" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#9cbb04" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dark grey blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#29465b" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:greeny brown" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#696006" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:lemon green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#adf802" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light periwinkle" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#c1c6fc" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:seaweed green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#35ad6b" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:sunshine yellow" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fffd37" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:ugly purple" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#a442a0" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:medium pink" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#f36196" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:puke brown" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#947706" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:very light pink" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fff4f2" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:viridian" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#1e9167" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:bile" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#b5c306" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:faded yellow" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#feff7f" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:very pale green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#cffdbc" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:vibrant green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#0add08" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:bright lime" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#87fd05" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:spearmint" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#1ef876" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light aquamarine" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#7bfdc7" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light sage" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#bcecac" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:yellowgreen" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#bbf90f" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:baby poo" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ab9004" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dark seafoam" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#1fb57a" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:deep teal" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#00555a" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:heather" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#a484ac" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:rust orange" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#c45508" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dirty blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#3f829d" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:fern green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#548d44" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:bright lilac" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#c95efb" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:weird green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#3ae57f" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:peacock blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#016795" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:avocado green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#87a922" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:faded orange" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#f0944d" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:grape purple" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#5d1451" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:hot green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#25ff29" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:lime yellow" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#d0fe1d" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:mango" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ffa62b" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:shamrock" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#01b44c" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:bubblegum" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ff6cb5" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:purplish brown" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#6b4247" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:vomit yellow" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#c7c10c" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:pale cyan" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#b7fffa" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:key lime" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#aeff6e" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:tomato red" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ec2d01" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:lightgreen" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#76ff7b" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:merlot" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#730039" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:night blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#040348" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:purpleish pink" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#df4ec8" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:apple" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#6ecb3c" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:baby poop green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#8f9805" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:green apple" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#5edc1f" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:heliotrope" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#d94ff5" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:yellow/green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#c8fd3d" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:almost black" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#070d0d" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:cool blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#4984b8" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:leafy green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#51b73b" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:mustard brown" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ac7e04" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dusk" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#4e5481" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dull brown" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#876e4b" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:frog green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#58bc08" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:vivid green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#2fef10" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:bright light green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#2dfe54" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:fluro green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#0aff02" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:kiwi" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#9cef43" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:seaweed" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#18d17b" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:navy green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#35530a" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:ultramarine blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#1805db" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:iris" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#6258c4" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:pastel orange" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ff964f" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:yellowish orange" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ffab0f" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:perrywinkle" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#8f8ce7" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:tealish" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#24bca8" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dark plum" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#3f012c" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:pear" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#cbf85f" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:pinkish orange" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ff724c" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:midnight purple" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#280137" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light urple" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#b36ff6" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dark mint" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#48c072" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:greenish tan" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#bccb7a" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light burgundy" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#a8415b" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:turquoise blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#06b1c4" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:ugly pink" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#cd7584" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:sandy" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#f1da7a" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:electric pink" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ff0490" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:muted purple" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#805b87" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:mid green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#50a747" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:greyish" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#a8a495" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:neon yellow" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#cfff04" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:banana" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ffff7e" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:carnation pink" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ff7fa7" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:tomato" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ef4026" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:sea" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#3c9992" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:muddy brown" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#886806" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:turquoise green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#04f489" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:buff" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fef69e" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:fawn" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#cfaf7b" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:muted blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#3b719f" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:pale rose" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fdc1c5" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dark mint green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#20c073" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:amethyst" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#9b5fc0" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:blue/green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#0f9b8e" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:chestnut" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#742802" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:sick green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#9db92c" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:pea" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#a4bf20" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:rusty orange" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#cd5909" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:stone" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ada587" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:rose red" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#be013c" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:pale aqua" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#b8ffeb" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:deep orange" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#dc4d01" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:earth" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#a2653e" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:mossy green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#638b27" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:grassy green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#419c03" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:pale lime green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#b1ff65" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light grey blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#9dbcd4" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:pale grey" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fdfdfe" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:asparagus" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#77ab56" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:blueberry" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#464196" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:purple red" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#990147" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:pale lime" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#befd73" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:greenish teal" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#32bf84" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:caramel" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#af6f09" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:deep magenta" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#a0025c" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light peach" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ffd8b1" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:milk chocolate" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#7f4e1e" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:ocher" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#bf9b0c" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:off green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#6ba353" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:purply pink" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#f075e6" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:lightblue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#7bc8f6" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dusky blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#475f94" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:golden" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#f5bf03" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light beige" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fffeb6" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:butter yellow" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fffd74" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dusky purple" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#895b7b" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:french blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#436bad" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:ugly yellow" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#d0c101" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:greeny yellow" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#c6f808" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:orangish red" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#f43605" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:shamrock green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#02c14d" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:orangish brown" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#b25f03" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:tree green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#2a7e19" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:deep violet" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#490648" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:gunmetal" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#536267" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:blue/purple" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#5a06ef" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:cherry" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#cf0234" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:sandy brown" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#c4a661" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:warm grey" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#978a84" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dark indigo" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#1f0954" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:midnight" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#03012d" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:bluey green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#2bb179" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:grey pink" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#c3909b" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:soft purple" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#a66fb5" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:blood" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#770001" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:brown red" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#922b05" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:medium grey" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#7d7f7c" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:berry" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#990f4b" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:poo" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#8f7303" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:purpley pink" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#c83cb9" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light salmon" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fea993" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:snot" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#acbb0d" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:easter purple" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#c071fe" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light yellow green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ccfd7f" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dark navy blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#00022e" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:drab" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#828344" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light rose" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ffc5cb" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:rouge" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ab1239" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:purplish red" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#b0054b" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:slime green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#99cc04" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:baby poop" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#937c00" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:irish green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#019529" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:pink/purple" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ef1de7" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dark navy" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#000435" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:greeny blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#42b395" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light plum" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#9d5783" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:pinkish grey" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#c8aca9" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dirty orange" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#c87606" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:rust red" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#aa2704" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:pale lilac" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#e4cbff" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:orangey red" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fa4224" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:primary blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#0804f9" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:kermit green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#5cb200" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:brownish purple" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#76424e" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:murky green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#6c7a0e" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:wheat" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fbdd7e" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:very dark purple" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#2a0134" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:bottle green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#044a05" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:watermelon" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fd4659" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:deep sky blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#0d75f8" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:fire engine red" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fe0002" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:yellow ochre" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#cb9d06" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:pumpkin orange" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fb7d07" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:pale olive" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#b9cc81" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light lilac" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#edc8ff" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:lightish green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#61e160" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:carolina blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#8ab8fe" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:mulberry" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#920a4e" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:shocking pink" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fe02a2" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:auburn" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#9a3001" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:bright lime green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#65fe08" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:celadon" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#befdb7" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:pinkish brown" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#b17261" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:poo brown" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#885f01" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:bright sky blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#02ccfe" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:celery" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#c1fd95" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dirt brown" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#836539" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:strawberry" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fb2943" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dark lime" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#84b701" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:copper" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#b66325" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:medium brown" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#7f5112" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:muted green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#5fa052" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:robin's egg" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#6dedfd" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:bright aqua" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#0bf9ea" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:bright lavender" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#c760ff" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:ivory" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ffffcb" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:very light purple" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#f6cefc" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light navy" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#155084" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:pink red" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#f5054f" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:olive brown" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#645403" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:poop brown" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#7a5901" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:mustard green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#a8b504" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:ocean green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#3d9973" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:very dark blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#000133" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dusty green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#76a973" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light navy blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#2e5a88" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:minty green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#0bf77d" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:adobe" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#bd6c48" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:barney" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ac1db8" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:jade green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#2baf6a" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:bright light blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#26f7fd" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light lime" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#aefd6c" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dark khaki" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#9b8f55" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:orange yellow" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ffad01" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:ocre" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#c69c04" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:maize" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#f4d054" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:faded pink" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#de9dac" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:british racing green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#05480d" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:sandstone" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#c9ae74" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:mud brown" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#60460f" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light sea green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#98f6b0" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:robin egg blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#8af1fe" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:aqua marine" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#2ee8bb" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dark sea green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#11875d" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:soft pink" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fdb0c0" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:orangey brown" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#b16002" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:cherry red" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#f7022a" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:burnt yellow" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#d5ab09" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:brownish grey" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#86775f" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:camel" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#c69f59" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:purplish grey" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#7a687f" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:marine" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#042e60" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:greyish pink" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#c88d94" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:pale turquoise" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#a5fbd5" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:pastel yellow" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fffe71" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:bluey purple" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#6241c7" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:canary yellow" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fffe40" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:faded red" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#d3494e" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:sepia" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#985e2b" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:coffee" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#a6814c" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:bright magenta" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ff08e8" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:mocha" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#9d7651" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:ecru" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#feffca" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:purpleish" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#98568d" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:cranberry" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#9e003a" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:darkish green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#287c37" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:brown orange" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#b96902" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dusky rose" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ba6873" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:melon" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ff7855" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:sickly green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#94b21c" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:silver" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#c5c9c7" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:purply blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#661aee" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:purpleish blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#6140ef" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:hospital green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#9be5aa" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:shit brown" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#7b5804" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:mid blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#276ab3" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:amber" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#feb308" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:easter green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#8cfd7e" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:soft blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#6488ea" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:cerulean blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#056eee" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:golden brown" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#b27a01" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:bright turquoise" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#0ffef9" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:red pink" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fa2a55" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:red purple" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#820747" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:greyish brown" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#7a6a4f" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:vermillion" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#f4320c" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:russet" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#a13905" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:steel grey" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#6f828a" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:lighter purple" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#a55af4" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:bright violet" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ad0afd" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:prussian blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#004577" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:slate green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#658d6d" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dirty pink" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ca7b80" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dark blue green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#005249" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:pine" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#2b5d34" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:yellowy green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#bff128" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dark gold" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#b59410" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:bluish" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#2976bb" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:darkish blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#014182" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dull red" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#bb3f3f" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:pinky red" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fc2647" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:bronze" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#a87900" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:pale teal" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#82cbb2" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:military green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#667c3e" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:barbie pink" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fe46a5" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:bubblegum pink" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fe83cc" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:pea soup green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#94a617" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dark mustard" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#a88905" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:shit" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#7f5f00" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:medium purple" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#9e43a2" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:very dark green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#062e03" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dirt" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#8a6e45" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dusky pink" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#cc7a8b" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:red violet" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#9e0168" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:lemon yellow" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fdff38" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:pistachio" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#c0fa8b" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dull yellow" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#eedc5b" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dark lime green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#7ebd01" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:denim blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#3b5b92" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:teal blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#01889f" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:lightish blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#3d7afd" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:purpley blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#5f34e7" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light indigo" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#6d5acf" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:swamp green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#748500" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:brown green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#706c11" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dark maroon" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#3c0008" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:hot purple" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#cb00f5" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dark forest green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#002d04" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:faded blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#658cbb" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:drab green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#749551" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light lime green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#b9ff66" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:snot green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#9dc100" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:yellowish" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#faee66" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light blue green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#7efbb3" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:bordeaux" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#7b002c" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light mauve" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#c292a1" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:ocean" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#017b92" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:marigold" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fcc006" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:muddy green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#657432" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dull orange" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#d8863b" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:steel" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#738595" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:electric purple" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#aa23ff" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:fluorescent green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#08ff08" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:yellowish brown" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#9b7a01" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:blush" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#f29e8e" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:soft green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#6fc276" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:bright orange" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ff5b00" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:lemon" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fdff52" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:purple grey" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#866f85" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:acid green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#8ffe09" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:pale lavender" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#eecffe" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:violet blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#510ac9" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light forest green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#4f9153" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:burnt red" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#9f2305" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:khaki green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#728639" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:cerise" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#de0c62" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:faded purple" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#916e99" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:apricot" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ffb16d" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dark olive green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#3c4d03" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:grey brown" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#7f7053" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:green grey" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#77926f" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:true blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#010fcc" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:pale violet" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ceaefa" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:periwinkle blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#8f99fb" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light sky blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#c6fcff" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:blurple" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#5539cc" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:green brown" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#544e03" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:bluegreen" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#017a79" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:bright teal" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#01f9c6" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:brownish yellow" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#c9b003" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:pea soup" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#929901" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:forest" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#0b5509" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:barney purple" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#a00498" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:ultramarine" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#2000b1" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:purplish" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#94568c" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:puke yellow" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#c2be0e" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:bluish grey" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#748b97" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dark periwinkle" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#665fd1" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dark lilac" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#9c6da5" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:reddish" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#c44240" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light maroon" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#a24857" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dusty purple" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#825f87" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:terra cotta" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#c9643b" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:avocado" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#90b134" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:marine blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#01386a" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:teal green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#25a36f" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:slate grey" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#59656d" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:lighter green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#75fd63" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:electric green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#21fc0d" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dusty blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#5a86ad" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:golden yellow" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fec615" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:bright yellow" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fffd01" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light lavender" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#dfc5fe" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:umber" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#b26400" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:poop" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#7f5e00" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dark peach" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#de7e5d" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:jungle green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#048243" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:eggshell" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ffffd4" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:denim" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#3b638c" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:yellow brown" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#b79400" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dull purple" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#84597e" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:chocolate brown" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#411900" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:wine red" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#7b0323" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:neon blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#04d9ff" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dirty green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#667e2c" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light tan" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fbeeac" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:ice blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#d7fffe" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:cadet blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#4e7496" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dark mauve" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#874c62" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:very light blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#d5ffff" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:grey purple" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#826d8c" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:pastel pink" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ffbacd" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:very light green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#d1ffbd" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dark sky blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#448ee4" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:evergreen" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#05472a" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dull pink" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#d5869d" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:aubergine" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#3d0734" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:mahogany" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#4a0100" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:reddish orange" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#f8481c" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:deep green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#02590f" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:vomit green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#89a203" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:purple pink" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#e03fd8" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dusty pink" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#d58a94" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:faded green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#7bb274" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:camo green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#526525" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:pinky purple" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#c94cbe" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:pink purple" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#db4bda" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:brownish red" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#9e3623" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dark rose" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#b5485d" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:mud" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#735c12" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:brownish" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#9c6d57" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:emerald green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#028f1e" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:pale brown" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#b1916e" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dull blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#49759c" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:burnt umber" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#a0450e" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:medium green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#39ad48" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:clay" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#b66a50" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light aqua" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#8cffdb" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light olive green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#a4be5c" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:brownish orange" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#cb7723" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dark aqua" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#05696b" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:purplish pink" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ce5dae" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dark salmon" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#c85a53" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:greenish grey" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#96ae8d" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:jade" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#1fa774" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:ugly green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#7a9703" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dark beige" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ac9362" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:emerald" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#01a049" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:pale red" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#d9544d" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light magenta" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fa5ff7" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:sky" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#82cafc" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light cyan" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#acfffc" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:yellow orange" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fcb001" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:reddish purple" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#910951" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:reddish pink" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fe2c54" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:orchid" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#c875c4" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dirty yellow" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#cdc50a" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:orange red" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fd411e" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:deep red" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#9a0200" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:orange brown" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#be6400" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:cobalt blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#030aa7" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:neon pink" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fe019a" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:rose pink" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#f7879a" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:greyish purple" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#887191" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:raspberry" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#b00149" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:aqua green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#12e193" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:salmon pink" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fe7b7c" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:tangerine" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ff9408" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:brownish green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#6a6e09" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:red brown" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#8b2e16" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:greenish brown" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#696112" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:pumpkin" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#e17701" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:pine green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#0a481e" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:charcoal" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#343837" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:baby pink" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ffb7ce" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:cornflower" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#6a79f7" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:blue violet" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#5d06e9" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:chocolate" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#3d1c02" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:greyish green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#82a67d" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:scarlet" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#be0119" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:green yellow" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#c9ff27" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dark olive" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#373e02" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:sienna" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#a9561e" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:pastel purple" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#caa0ff" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:terracotta" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ca6641" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:aqua blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#02d8e9" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:sage green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#88b378" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:blood red" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#980002" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:deep pink" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#cb0162" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:grass" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#5cac2d" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:moss" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#769958" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:pastel blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#a2bffe" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:bluish green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#10a674" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:green blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#06b48b" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dark tan" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#af884a" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:greenish blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#0b8b87" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:pale orange" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ffa756" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:vomit" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#a2a415" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:forrest green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#154406" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dark lavender" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#856798" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dark violet" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#34013f" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:purple blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#632de9" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dark cyan" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#0a888a" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:olive drab" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#6f7632" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:pinkish" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#d46a7e" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:cobalt" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#1e488f" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:neon purple" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#bc13fe" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light turquoise" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#7ef4cc" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:apple green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#76cd26" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dull green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#74a662" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:wine" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#80013f" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:powder blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#b1d1fc" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:off white" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ffffe4" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:electric blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#0652ff" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dark turquoise" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#045c5a" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:blue purple" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#5729ce" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:azure" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#069af3" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:bright red" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ff000d" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:pinkish red" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#f10c45" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:cornflower blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#5170d7" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light olive" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#acbf69" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:grape" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#6c3461" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:greyish blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#5e819d" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:purplish blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#601ef9" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:yellowish green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#b0dd16" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:greenish yellow" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#cdfd02" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:medium blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#2c6fbb" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dusty rose" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#c0737a" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light violet" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#d6b4fc" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:midnight blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#020035" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:bluish purple" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#703be7" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:red orange" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fd3c06" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dark magenta" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#960056" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:greenish" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#40a368" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:ocean blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#03719c" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:coral" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fc5a50" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:cream" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ffffc2" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:reddish brown" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#7f2b0a" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:burnt sienna" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#b04e0f" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:brick" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#a03623" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:sage" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#87ae73" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:grey green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#789b73" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:white" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ffffff" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:robin's egg blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#98eff9" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:moss green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#658b38" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:steel blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#5a7d9a" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:eggplant" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#380835" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light yellow" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fffe7a" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:leaf green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#5ca904" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light grey" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#d8dcd6" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:puke" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#a5a502" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:pinkish purple" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#d648d7" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:sea blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#047495" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:pale purple" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#b790d4" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:slate blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#5b7c99" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:blue grey" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#607c8e" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:hunter green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#0b4008" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:fuchsia" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ed0dd9" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:crimson" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#8c000f" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:pale yellow" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ffff84" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:ochre" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#bf9005" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:mustard yellow" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#d2bd0a" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light red" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ff474c" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:cerulean" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#0485d1" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:pale pink" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ffcfdc" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:deep blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#040273" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:rust" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#a83c09" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light teal" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#90e4c1" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:slate" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#516572" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:goldenrod" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fac205" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dark yellow" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#d5b60a" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dark grey" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#363737" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:army green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#4b5d16" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:grey blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#6b8ba4" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:seafoam" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#80f9ad" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:puce" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#a57e52" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:spring green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#a9f971" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dark orange" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#c65102" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:sand" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#e2ca76" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:pastel green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#b0ff9d" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:mint" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#9ffeb0" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light orange" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fdaa48" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:bright pink" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fe01b1" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:chartreuse" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#c1f80a" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:deep purple" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#36013f" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dark brown" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#341c02" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:taupe" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#b9a281" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:pea green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#8eab12" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:puke green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#9aae07" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:kelly green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#02ab2e" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:seafoam green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#7af9ab" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:blue green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#137e6d" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:khaki" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#aaa662" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:burgundy" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#610023" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dark teal" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#014d4e" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:brick red" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#8f1402" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:royal purple" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#4b006e" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:plum" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#580f41" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:mint green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#8fff9f" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:gold" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#dbb40c" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:baby blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#a2cffe" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:yellow green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#c0fb2d" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:bright purple" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#be03fd" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dark red" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#840000" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:pale blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#d0fefe" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:grass green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#3f9b0b" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:navy" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#01153e" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:aquamarine" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#04d8b2" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:burnt orange" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#c04e01" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:neon green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#0cff0c" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:bright blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#0165fc" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:rose" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#cf6275" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light pink" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ffd1df" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:mustard" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ceb301" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:indigo" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#380282" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:lime" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#aaff32" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:sea green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#53fca1" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:periwinkle" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#8e82fe" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dark pink" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#cb416b" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:olive green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#677a04" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:peach" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ffb07c" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:pale green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#c7fdb5" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light brown" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ad8150" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:hot pink" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ff028d" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:black" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#000000" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:lilac" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#cea2fd" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:navy blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#001146" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:royal blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#0504aa" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:beige" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#e6daa6" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:salmon" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ff796c" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:olive" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#6e750e" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:maroon" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#650021" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:bright green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#01ff07" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dark purple" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#35063e" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:mauve" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ae7181" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:forest green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#06470c" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:aqua" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#13eac9" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:cyan" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#00ffff" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:tan" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#d1b26f" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dark blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#00035b" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:lavender" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#c79fef" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:turquoise" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#06c2ac" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dark green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#033500" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:violet" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#9a0eea" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light purple" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#bf77f6" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:lime green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#89fe05" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:grey" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#929591" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:sky blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#75bbfd" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:yellow" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ffff14" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:magenta" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#c20078" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#96f97b" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:orange" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#f97306" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:teal" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#029386" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#95d0fc" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:red" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#e50000" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:brown" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#653700" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:pink" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#ff81c0" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#0343df" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#15b01a" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:purple" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#7e1e9c" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:gray teal" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#5e9b8a" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:purpley gray" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#947e94" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light gray green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#b7e1a1" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:reddish gray" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#997570" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:battleship gray" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#6b7c85" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:charcoal gray" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#3c4142" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:grayish teal" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#719f91" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:gray/green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#86a17d" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:cool gray" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#95a3a6" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dark blue gray" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#1f3b4d" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:bluey gray" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#89a0b0" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:greeny gray" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#7ea07a" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:bluegray" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#85a3b2" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light blue gray" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#b7c9e2" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:gray/blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#647d8e" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:brown gray" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#8d8468" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:blue/gray" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#758da3" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:grayblue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#77a1b5" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dark gray blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#29465b" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:grayish" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#a8a495" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light gray blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#9dbcd4" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:pale gray" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#fdfdfe" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:warm gray" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#978a84" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:gray pink" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#c3909b" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:medium gray" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#7d7f7c" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:pinkish gray" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#c8aca9" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:brownish gray" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#86775f" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:purplish gray" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#7a687f" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:grayish pink" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#c88d94" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:grayish brown" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#7a6a4f" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:steel gray" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#6f828a" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:purple gray" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#866f85" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:gray brown" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#7f7053" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:green gray" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#77926f" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:bluish gray" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#748b97" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:slate gray" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#59656d" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:gray purple" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#826d8c" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:greenish gray" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#96ae8d" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:grayish purple" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#887191" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:grayish green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#82a67d" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:grayish blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#5e819d" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:gray green" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#789b73" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:light gray" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#d8dcd6" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:blue gray" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#607c8e" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:dark gray" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#363737" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:gray blue" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#6b8ba4" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
<code class="language-plaintext highlighter-rouge" style="white-space: nowrap;">
"xkcd:gray" <span><svg width="16" height="16" viewBox="0 0 16 16">
        <rect width="16" height="16" fill="#929591" stroke="black" stroke-width="2"/>
    </svg></span>
</code> &nbsp;
