# minline

A line editing library in pure Nim designed to be easy to use and provide a minimal (but useful) set of features to build interactive CLI applications.

*minline* provides:

* Basic line editing functionality, move the cursor left and right, delete characters etc.
* Support for a simple prompt at the beginning of the line.
* Support for hiding typed characters (and print asterisks instead).
* Support for intercepting keypresses before they are printed to stdout.
* Some Emacs-like keybindings.
* Customizable line completion.
* Customizable key bindings (i.e. bind a key or a sequence of keys to a Nim proc).
* Persistent history management (history entries can be written to a file).

*minline* does *not* provide:

* Support for multiple lines (you will not be able to move to the next line)
* Support for Unicode or characters other than ASCII.
* Support for colors in the prompt.
* Full Emacs or Vi key bindings.

For more information, see [the reference docs](https://h3rald.com/minline/minline.html).
