# EXAPUNKS Syntax
[![License](https://img.shields.io/github/license/jwortmann/exapunks-syntax.svg)](https://github.com/jwortmann/exapunks-syntax/blob/master/LICENSE)

This package for [Sublime Text](https://www.sublimetext.com/) provides syntax highlighting for the assembly language used in the game [EXAPUNKS](http://www.zachtronics.com/exapunks/).

## Usage

Copy the files `Exapunks.sublime-syntax` and `Exapunks.sublime-settings` into your user directory of Sublime Text.
To find the location of your user directory, click on `Preferences > Browse Packages...` within Sublime Text.

Due to there beeing no convention of a specific file extension for EXAPUNKS code, you have to manually select EXAPUNKS
in the rightmost part of the status bar to apply syntax highlighting for the current file.
Alternatively you can add the expression `NOTE EXAPUNKS` as a first line into your source code, to automatically apply
the EXAPUNKS syntax whenever that file is opened.

## Screenshot

The actual highlighting colors depend on the chosen color scheme. This is how it will look for the default color schemes
*Monokai*, *Breakers* and *Mariana*:
![Screenshot](https://raw.githubusercontent.com/jwortmann/exapunks-syntax/master/screenshot.png)

## License

Released under the [Apache 2.0 License](https://github.com/jwortmann/exapunks-syntax/blob/master/LICENSE).