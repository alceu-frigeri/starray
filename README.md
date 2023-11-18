starray
==========

This is a structured (properties) array (hash) package based on expl3.

For more details,  see the documentation,
[starray.pdf](http://mirrors.ctan.org/macros/latex/contrib/starray/doc/starray.pdf)

--------------

## Requirements
* none besides a fairly recent LaTeX distribution as recent as 2022/06/01
(with the new in kernel *\ProcessKeyOptions* and *\NewDocumentCommand*)

## Installation
The stable version is available at [CTAN](https://ctan.org/pkg/starray).

## Usage
### Stable version
Just place
```latex
  \usepackage{starray}
```

in the preamble and compile away.


Be aware that options might change between versions, so you have to check them manually.

## More Information and documentation
More Information can be found in the documentation; you can find a  "bleeding edge" version
at [the github page](http://github.com/alceu-frigeri/starray)

## Contacting Author

For bug reports and enhancement suggestions, the preferred way is to use
[the project's issue page](https://github.com/alceu-frigeri/starray/issues).
Please be ready to provide an example code showing the bug, if any.

Please do not use the issue page for generic help on how to use the package.

* git: https://github.com/alceu-frigeri/starray

-------------
Copyright 2023 by Alceu Frigeri

 This work may be distributed and/or modified under the
 conditions of

 * The [LaTeX Project Public License](http://www.latex-project.org/lppl.txt), version 1.3c (or later), and/or
 * The [GNU Affero General Public License](https://www.gnu.org/licenses/agpl-3.0.html), version 3 (or later)

This work has the LPPL maintenance status *maintained*.

The Current Maintainer of this work is Alceu Frigeri

-------------
## This work consists of the files

* starray.sty
    - The Package itself

* README.md (this file)
    - quick introduction

* starray.tex
    - package documentation

* starray.pdf
    - documentation in PDF format

-------------

## Changelog

* Version 1.4 (this) 
    - added a few functions _set_iter_from_hash:nn and _iterate_over:n.

* Version 1.3 
    - Fixed issue #4, where (in some instances) _set_from_keyval could render a quark loop.

* Version 1.2
    - Issues #3
    - added expandable versions of some commands (see manual)
    - documentation

* Version 1.1
    - Issues #1/#2
    - most/all commands are protected now
    - removed predicate version of conditionals
    - documentation


* Version 1.0
    - Initial release  by CTAN.
