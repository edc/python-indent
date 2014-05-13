python-indent
=============

Vim indentation for Python that uses both visual and traditional shift indent, adapted from http://www.vim.org/scripts/script.php?script_id=974

As with the origianal indent script, visual indentation is used within open parenthesis. To be compliant with PEP 8 suggestion, this script uses regular shift indentation instead of visual indentation when the open parenthesis ends its line. For example,

```
box.open("knife",

```

would trigger the visual indentation on the new line, but

```
box.open(
```

would trigger the regular shift indentation.

### Installation

With pathogen, just clone this repo into `~/.vim/bunder/`. Without pathogen, put the `python.vim` file under `~/.vim/indent/`.
