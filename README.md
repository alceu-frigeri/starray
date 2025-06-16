starray
==========

This is a structured (properties) array (hash) package based on expl3.

For more details,  see the documentation,
[starray.pdf](http://mirrors.ctan.org/macros/latex/contrib/starray/doc/starray.pdf)

--------------

## Requirements
* none besides a fairly recent LaTeX distribution as recent as 2023/11/01
(with the new in kernel *\ProcessKeyOptions* and *\NewDocumentCommand* and *\prop_new_linked:*)

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
Copyright 2023-present by Alceu Frigeri

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
* Version 1.9c (next)
    - fixing issue (#8)[https://github.com/alceu-frigeri/starray/issues/8].
    - (hopefully) better documentation
    - example of use added (finally 'fixing' (#5)[https://github.com/alceu-frigeri/starray/issues/5]), in (demo)[https://github.com/alceu-frigeri/starray/tree/main/demo]
    
* Version 1.9b (this) 
    - fixing issue #7 (related to https://github.com/latex3/latex3/issues/1189) and removing the (unneeded) ```predicate``` in variant generation of ``` \starray_(g)set_prop:nnn```.

* Version 1.9 
    - Removing some internal structures (_base_prop, _def_prop) deprecated by the last three updates.

* Version 1.8
    - code speedup thanks to 'linked' property lists. Code now relies on a more recent l3kernel.

* Version 1.7
    - code cleanup. Still related to issues: #6, https://github.com/latex3/latex3/issues/1460 and https://github.com/latex3/latex3/issues/1466
    - documented \starray_get_uniqueID (helper function, see documentation)

* Version 1.6
    - removing all V-expansion of property/sequence lists to avoid further issues with l3kernel 
      issues: #6, https://github.com/latex3/latex3/issues/1460 and https://github.com/latex3/latex3/issues/1466
    - Remarks: code is operational but needs further cleanup!

* Version 1.5
    - added \starray_term_syntax:nNN variant and friends (\starray_parsed_ ... :NN ) the _parsed_ ones being expandable

* Version 1.4
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
