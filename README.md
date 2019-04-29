# EXAPUNKS Syntax

[![License](https://img.shields.io/github/license/jwortmann/exapunks-syntax.svg)](https://github.com/jwortmann/exapunks-syntax/blob/master/LICENSE)

This package for [Sublime Text 3](https://www.sublimetext.com/) provides syntax highlighting for the assembly language used in the game [EXAPUNKS](http://www.zachtronics.com/exapunks/).

## Usage

Copy the files [Exapunks.sublime-syntax](https://raw.githubusercontent.com/jwortmann/exapunks-syntax/master/Exapunks.sublime-syntax) and [Exapunks.sublime-settings](https://raw.githubusercontent.com/jwortmann/exapunks-syntax/master/Exapunks.sublime-settings) into a folder in the packages directory of Sublime Text, e.g. your User package.
To find the location of your User package, choose `Preferences > Browse Packages...` within Sublime Text and open the folder `User`.

There is no convention for a specific file extension of EXAPUNKS code that I'm aware of, but if you use the file extension `.exapunks`, syntax highlighting should be applied to your files.
Alternatively you can manually select *User/EXAPUNKS* under `View > Syntax` from the menu or add the expression `NOTE EXAPUNKS` as a first line into your source code to automatically apply the EXAPUNKS syntax, whenever that file is opened.

## Preview

The actual highlighting colors depend on the chosen color scheme.
The following image shows a preview for the default color schemes *Monokai*, *Sixteen* and *Mariana*:
![Screenshot](https://raw.githubusercontent.com/jwortmann/exapunks-syntax/master/screenshot.png)

Some of the syntax rules were updated to follow Sublime Text's scope naming guidelines and assign more specific scopes.
Depending on the chosen color scheme, highlighting colors might have changed when compared to a [previous version](https://github.com/jwortmann/exapunks-syntax/tree/legacy) of the syntax definition file.
