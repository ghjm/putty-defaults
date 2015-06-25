# putty-defaults

These are just my preferred settings for PuTTY. I load these as default settings within PuTTY itself, and then use [Putty Madness](https://github.com/ghjm/PuttyMadness) to remember my sessions.

The settings in this file include:

* Font set to 11-point [Inconsolata](http://www.levien.com/type/myfonts/inconsolata.html), with much gratitude to Ralph Levien.
* Green on black ("The Matrix") color scheme, with everything readable.
* Set character set to UTF-8.
* 20000 lines of scrollback.
* 60 second keepalives.
* SSH v2 only.
* Agent forwarding and X11 forwarding enabled by default.

I have not changed the terminal type string from "xterm" because I connect to a lot of different boxes, some of them ancient, and the PuTTY-specific terminal types aren't always available. I find that xterm with UTF-8 works well enough for my purposes.

