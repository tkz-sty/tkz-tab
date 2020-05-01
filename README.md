# tkz-tab – Tables of signs and variations using PGF/TikZ

Release 2.12c 2020/04/29

## Description

The `tkz-tab` package is built on top of PGF and its associated front-end,
 TikZ and is a (La)TeX-friendly drawing package. The aim is to provide some
useful macros  to build  tables showing variations  of functions as they are
used in France.
These macros may be used by only LaTeX TeX users. The documentation is in
 French.

## Licence

This work may be distributed and/or modified under the
conditions of the LaTeX Project Public License, either version 1.3
of this license or (at your option) any later version.
The latest version of this license is in
[LaTeX Project Public License](https://www.latex-project.org/lppl/)
 and version 1.3 or later is part of all distributions of LaTeX version 2005/12/01 or later.

This work has the LPPL maintenance status “maintained”.

The Current Maintainer of this work is Alain Matthes.


## Requirements

The package compiles with utf8, pdflatex and lualatex.
The package loads `TikZ` and you can use it.

## Installation

The package `tkz-tab` is present in TeXLive and MiKTeX, use the package
manager to install.

You can experiment with the `tkz-tab` package by placing all of the
distribution files in the directory containing your current tex file.

The different files must be moved into the different directories in your
installation `TDS` tree or in your `TEXMFHOME`:

```
  doc/TKZdoc-tab.pdf   -> TDS:doc/latex/tkz-tab/TKZdoc-tab.pdf
  doc/README.md        -> TDS:doc/latex/tkz-tab/README.md
  doc/latex/*.*        -> TDS:doc/latex/tkz-tab/latex/*.*
  latex/tkz-tab.sty    -> TDS:tex/latex/tkz-tab/tkz-tab.sty
```

## Documentation

Documentation for `tkz-tab` is available on `CTAN`. You will soon be able to find examples on my site [http://altermundus.fr](http://altermundus.fr).


## History

- v2.11 correction of a bug in the macro `\tkzTabSetup`.
- v2.1  correction of bugs and add examples in the documentation.

## Author

Alain Matthes, 5 rue de Valence, Paris 75005, al (dot) ma (at) mac (dot) com
