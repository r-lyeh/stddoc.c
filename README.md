# stddoc.c
- _stddoc.c_ is a tiny documentation generator for 60 programming languages.
- Check auto-generated [sample page here](https://rawgit.com/r-lyeh/stddoc.c/master/stddoc.c.html)

# How does it work?
- Markdeep code comments are extracted from stdin and printed into stdout as a HTML file.

# Usage
- `stddoc < source.code > documentation.html`
- `type *.code | stddoc > documentation.html`

# Supported languages
Language                | `/// comment`      | `--- comment` | `### comment`
------------------------|:-------------------|:--------------|:-------------------
ActionScript            | Yes                |               |
Ada                     |                    | Yes           |
AngelScript             | Yes                |               |
AppleScript             |                    | Yes           |
AWK                     |                    |               | Yes
Bash                    |                    |               | Yes
Bourne shell            |                    |               | Yes
C (C99)                 | Yes                |               |
C shell                 |                    |               | Yes
C#                      | Yes                |               |
C++                     | Yes                |               |
ChaiScript              | Yes                |               |
Cobra                   |                    |               | Yes
D                       | Yes                |               |
Dao                     |                    |               | Yes
Eiffel                  |                    | Yes           |
Euphoria                |                    | Yes           |
GameMonkey              | Yes                |               |
GML                     | Yes                |               |
Go                      | Yes                |               |
Haskell                 |                    | Yes           |
Java                    | Yes                |               |
JavaScript              | Yes                |               |
JetScript               | Yes                |               |
jtc                     | Yes                |               |
Jx9                     | Yes                |               |
Kotlin                  | Yes                |               |
Lua                     |                    | Yes           |
Maple                   |                    |               | Yes
Neko                    | Yes                |               |
Object Pascal (Delphi)  | Yes                |               |
Objective-C             | Yes                |               |
Occam                   |                    | Yes           |
Pawn                    | Yes                |               |
Perl                    |                    |               | Yes
Perl6                   |                    |               | Yes
PHP                     | Yes                |               | Yes
PowerShell              |                    |               | Yes
PSL                     |                    | Yes           |
Python                  |                    |               | Yes
QuakeC                  | Yes                |               |
R                       |                    |               | Yes
Ruby                    |                    |               | Yes
Rust                    | Yes                |               |
SASS                    | Yes                |               |
Scala                   | Yes                |               |
Seed7                   |                    |               | Yes
SGML                    |                    | Yes           |
SGScript                | Yes                |               |
SPARK                   |                    | Yes           |
SQL                     |                    | Yes           |
Squirrel                | Yes                |               |
Swift                   | Yes                |               |
Tcl                     |                    |               | Yes
Terra                   |                    | Yes           |
TSQL                    |                    | Yes           |
Vala                    | Yes                |               |
VHDL                    |                    | Yes           |
Wren                    | Yes                |               |
Xojo                    | Yes                |               |

# Changelog
- 2018/01/07 (v1.0.0):  Initial version

# License
- Unlicensed (~Public Domain).
- Using API doc style created by [Aras Pranckevičius](https://github.com/aras-p).
- Using Markdeep by [Morgan McGuire](https://casual-effects.com/markdeep/).
