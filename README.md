# Anzio Alpha Basic Support for Visual Studio Code

## Features

Basic syntax highlighting which recognizes:

* Variables
* Labels (i.e. functions, e.g. `SOME'CODE'BLOCK:`)
* Function Calls (e.g. `TAB(10)`)
* EES-Specific identifiers (e.g. `DB2`)
* Multi-line comments\*

\*From the OneNote:

>An "&" embedded in (i.e. not at the end of) a comment is ignored, but an "&" at the end of a comment not itself following an "&" causes continuation of the line __**from that point, i.e. the next line is pulled into the comment.**__

The syntax highlighter can recognize such multiline comments to help avoid these kinds of mistakes.

### 1.0.3

* Add support for the file extension .inc

### 1.0.2

* Treat optional line numbers at the beginning of lines as comments.
* Disable keyword highlighting when part of a label.
* Add support for the following file extensions:
    * .lsx
    * .map
    * .io
    * .qry

### 1.0.1

* Don't treat `\"` as an escape character.

### 1.0.0

* Initial release.
