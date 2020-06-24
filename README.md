st - simple terminal
--------------------
st is a simple terminal emulator for X which sucks less.


Requirements
------------
In order to build st you need the Xlib header files.

`tty-joypixel`

`libx-bgra`


Installation
------------
Edit config.mk to match your local setup (st is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install st (if
necessary as root):

    make clean install

Bindings
-----------
**scrollback** with `alt-↑/↓` or `alt-i/k`.

**zoom/change font size**: `alt-shift-↑/↓` or `al-shift-i/k`; `alt-home` returns to default.

**copy text** with `alt-c`, **paste** is `alt-v`.



