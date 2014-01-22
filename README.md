Cool Syntax Highlighter for Sublime Text
========================

A basic syntax highlighter for the Cool (Classroom Object-Oriented Language) programming language.

Installation
-----------

The easiest way to install the package is through the [Package Control](https://sublime.wbond.net/installation). Once you have Package Control installed, type `Ctrl`+`Shift`+`P` (`Cmd`+`Shift`+`P` on Mac) and select the `Package Control: Install Package` command. Select the `Cool` package and wait for it to install.

Usage
-----

Once the package is installed, there will be a language option for Cool (located in the bottom right corner of the window). Unfortuantely, Cool and Lisp share the `.cl` file extension, so you may find that `.cl` files still default to the Lisp highlighter. To change this to Cool, simply click in the bottom right corner of the window where it says Lisp and select Cool from the dropdown.

Bug Reporting
----

This syntax highlighter is still in development. If you discover an issue with the highlighter, please report it in the [issues](https://github.com/princjef/sublime-cool-highlighter/issues) section of this repository. Feel free to fork and pull request if you would like to fix a bug/add a feature yourself.

Contributing
-------

If you would like to contribute to the repository (either via bugfixes or added awesomeness), you can fork the repository and submit a pull request with your changes. The highlighter is written in conjunction with [AAAPackageDev](https://github.com/SublimeText/AAAPackageDev), so take a look there if you want to learn how to edit the highlighter. There is also a [tutorial](http://docs.sublimetext.info/en/latest/extensibility/syntaxdefs.html) from Sublime Text to help you out.

Whatever you decide to do, please make changes to the `cool.JSON-tmLanguage` file, then convert it to a `.tmLanguage` file using [AAAPackageDev](https://github.com/SublimeText/AAAPackageDev). Any pull requests that change `cool.tmLanguage` without changing `cool.JSON-tmLanguage` will be rejected. Thanks for your help!
