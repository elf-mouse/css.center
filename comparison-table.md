# [Absolute Centering](http://codepen.io/shshaw/full/gEiDt)

Technique | Browser Support | Responsive | Overflow | `resize:both` | Variable Height | Major Caveats
--------- | --------------- | ---------- | -------- | ------------- | --------------- | -------------
Absolute Centering | Modern & IE8+ | Yes | Scroll, can overflow container | Yes | Yes* | Variable Height not perfect cross-browser
Negative Margins | All | No | Scroll | Resizes but doesn't stay centered | No | Not responsive, margins must be calculated manually
Transforms | Modern & IE9+ | Yes | Scroll, can overflow container | Yes | Yes | Blurry rendering
Table-Cell | Modern & IE8+ | Yes | Expands container | No | Yes | Extra markup
Inline-Block | Modern, IE8+ & IE7* | Yes | Expands container | No | Yes | Requires container, hacky styles
Flexbox | Modern & IE10+ | Yes | Scroll, can overflow container | Yes | Yes | Requires container, vendor prefixes
