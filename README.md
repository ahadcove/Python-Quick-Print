# Python Quick Print

Quickly print out log messages

![](images/demo.gif)

## Installing

This extension is available for free in the [Visual Studio Code Marketplace](https://marketplace.visualstudio.com/items?itemName=AhadCove.python-quick-print)

## Warning
This uses Python 3 syntax,
If you're using Python 2 print isn't a function.
You can import this behavior from __future__:

`from __future__ import print_function`

## How to use

#### Only activates with .py files

* Highlight anything in the editor
* Press `Cmd+Shift+L` (Mac), or `Ctrl+Shift+L` (Windows)
* The output (on a new line) will be: `print('variable:', variable)`

#### Keyboard Shortcut
By default the keyboard shortcut is `Cmd+Shift+L` or `Ctrl+Shift+L`
If this shortcut interferes with another extension or system wide Shortcut, you may change it in the `Keyboard Shortcuts Setting`.

Press `Cmd+P` or `Ctrl+P` and type in `Open Keyboard Shortcuts`.
Search for `Print Python Selection` and click on the `pen icon`.
This is where you can enter any `Shortcut` you choose.

## License
[MIT License](LICENSE)
