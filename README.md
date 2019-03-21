[language-kaoscript](https://atom.io/packages/language-kaoscript)
=================================================================

[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg?style=flat)](./LICENSE)
[![Syntax Version](https://img.shields.io/badge/syntax-v0.2%20/%20oudated-critical.svg?style=flat)](https://github.com/kaoscript/kaoscript)

Adds syntax highlighting and snippets to [kaoscript](https://github.com/kaoscript/kaoscript) files in [Atom](http://atom.io/).

Getting Started
---------------

### Atom Preferences

Search and install the package `language-kaoscript` in Atom (Preferences->Install)

### apm

With [apm](https://github.com/atom/apm) previously installed:

	apm install language-kaoscript

Snippets
--------

| Trigger       | Name                     | Body                             |
| ------------- | ------------------------ | -------------------------------- |
| class         | class                    | class $name {...}                |
| do            | do while                 | do {...} while $condition        |
| dou           | do until                 | do {...} until $condition        |
| enum          | enum                     | enum $name {...}                 |
| if            | if                       | if $condition {...}              |
| ife           | if … else                | if $condition {...} else {...}   |
| else          | else                     | else {...}                       |
| elseif        | else if                  | else if $condition {...}         |
| fortil        | for from/til             | for $variable from $ til $ {...} |
| forto         | from from/to             | for $variable from $ to $ {...}  |
| forin         | for in                   | for $variable in $ {...}         |
| forof         | for of                   | for $variable of $ {...}         |
| fun           | function                 | func $name($) {...}              |
| f             | anonymous function       | func($) {...}                    |
| log           | log                      | console.log($)                   |
| warn          | warn                     | console.warn($)                  |
| error         | error                    | console.error($)                 |
| try           | try                      | try {...}                        |
| tryc          | try catch                | try {...} catch $error {...}     |
| tryf          | try finally              | try {...} finally {...}          |
| until         | until                    | until $condition {...}           |
| while         | while                    | while $condition {...}           |

License
-------

[MIT](http://www.opensource.org/licenses/mit-license.php) &copy; Baptiste Augrain