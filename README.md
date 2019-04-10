# EXAPUNKS Syntax

[![License](https://img.shields.io/github/license/jwortmann/exapunks-syntax.svg)](https://github.com/jwortmann/exapunks-syntax/blob/master/LICENSE)

This package for [Sublime Text 3](https://www.sublimetext.com/) provides syntax highlighting for the assembly language used in the game [EXAPUNKS](http://www.zachtronics.com/exapunks/).

## Usage

Copy the files `Exapunks.sublime-syntax` and `Exapunks.sublime-settings` into your user directory of Sublime Text.
To find the location of your user directory, click on `Preferences > Browse Packages...` within Sublime Text and open the folder `User`.

There is no convention for a specific file extension of EXAPUNKS code, but if you use the file extension `.exapunks`, syntax highlighting should be applied to your files.
Alternatively you can manually select *User/EXAPUNKS* under `View > Syntax` or add the expression `NOTE EXAPUNKS` as a first line into your source code to automatically apply the EXAPUNKS syntax, whenever that file is opened.

## Screenshot

The actual highlighting colors depend on the chosen color scheme.
This is how it will look with the default color schemes *Monokai*, *Breakers* and *Mariana*:
![Screenshot](https://raw.githubusercontent.com/jwortmann/exapunks-syntax/master/screenshot.png)

## License

Released under the [Apache 2.0 License](https://github.com/jwortmann/exapunks-syntax/blob/master/LICENSE).
