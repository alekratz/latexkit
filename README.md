# LaTeXkit
A LaTeX renderer for XKit.

# Installing
This requires XKit. You can find them at https://github.com/new-xkit/XKit

I have no idea how to distribute this thing! So for now, follow these instructions:

1. Open up https://www.tumblr.com/xkit_editor
2. Click "new extension" (or press ctrl-E)
3. Copy-paste the contents of the [latexkit.js](https://raw.githubusercontent.com/alekratz/latexkit/master/latexkit.js) file into the Script (first) tab, and the contents of [latexkit.icon.js](https://raw.githubusercontent.com/alekratz/latexkit/master/latexkit.icon.js) into the Icon (third) tab.
4. You should be good to go.

# Using
The main caveat of using this plugin is that it cannot interpret a combination of LaTeX and regular text. In order to have your LaTeX run, you must do one of the following:
* Surround your LaTeX with \begin and \end statements. For example:
** `\begin\(\LaTeX\)\end`
* In HTML editing mode, surround your LaTeX with `<div class="latex"></div>`

# Information
For news and support, you can check out http://latexkit.tumblr.com.

# Bugs
**This is beta software.** Bugs are bound to happen. If they do, please create an issue in issues section, or send me an ask on http://latexkit.tumblr.com.

# License
Software WTFPL, see LICENSE for details.

Thanks to [Andreas Grech](http://knowledge-aholic.blogspot.com) for his implementation of LaTeX rendering using JQuery. That, and he was the first hit on Google ;)