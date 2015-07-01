#OrigamiColorHighlighter

_OrigamiColorHighlighter is a plugin for the Sublime Text 2 and 3, which shows Origami colors in code._

![ ](https://cloud.githubusercontent.com/assets/85783/8474723/10a7b144-20aa-11e5-92a3-af87f88b8885.png)

This package is a fork of [ColorHighlighter](https://github.com/Monnoroch/ColorHighlighter).

**Installation :**

- **_Recommended_** - Using [Sublime Package Control](https://packagecontrol.io/ "Sublime Package Control")
    - `ctrl+shft+p` then select `Package Control: Install Package`
    - install `Origami Color Highlighter`
- Alternatively, download the package from [GitHub](https://github.com/Financial-Times/OrigamiColorHighlighter "OrigamiColorHighlighter") into your `Packages` folder
- For icons install [ImageMagick](http://www.imagemagick.org/)

**Usage :**

Just click or move the cursor (or multiple cursors) on the color code e.g. "#FFFFFF" and it'll be highlighted with its real color.
These color formats are currently supported:
- All CSS color formats.
- Hexadecimal RGBA ("#FFFFFFFF").
- Hexadecimal ARGB ("#FFFFFFFF") (if you set the setting argb to true).
- Named colors like "green", "black" and many others.
- Less/sass/scss/stylus variables (supports importing from another files).
- [VAL, VAL, VAL] and [VAL, VAL, VAL, VAL] when editing *.sublime-theme files. Where VAL can be the following:
  - An integer: from 0 to 255.
  - A float value from 0.0 to 1.0, you can also skip leading zero (like that: .25)
  - A percentage from 0% to 100%.

**Settings :**

You can choose the highliting style from:
- "Filled", "outlined", "none" in ST2.
- "Filled", "outlined", "none", "underlined" (solid, strippled, squiggly) in ST3.

You can also turn on highlighting all colors at once. This mode has own highlighting style, so you can highlight all colors with underline and selected colors with filled rect.

You can also enable icons, which will be shown in the gutter of a file (ST3 only).

You can also set OrigamiColorHighlighter to use Hexadecimal ARGB instead of RGBA.

You can always turn off default keybindings via main menu.
