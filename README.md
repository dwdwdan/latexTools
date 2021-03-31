# README

This package is essentially my standard preamble wrapped in a package form.

This document will also form the documentation.

## Included Packages
This package imports a lot of other packages, namely 
- amsmath
- amssymb
- amsthm
- subfiles
- tabu
- xcolor
- soul
- mathtools
- graphicx
- hyperref
- cleveref
- cancel
- bm
- nicefrac

## amsthm environments
These are used 
````tex
\begin{theorem}
	...BLOCK...
\end{theorem}
````
### Numbered
Each of these is numbered with the same counter, at the subsection level
- theorem
- lemma
- proposition
- definition

### Unnumbered
The following are not numbered
- solution
- claim
- theorem*

## Blackboard Bold
Many letters have blackboard bold variants invoked by `\IN` for blackboard bold N.

## Math Operators
Various Math Operators are also defined:
- arcsec
- arccsc
- arccot
- hcf
- proj
- re
- bin
- poi
- geo

## Some Renamings
Some commands have also been renamed.
- `\tendsto` gives a long right arrow, used for limits
- `\swap` gives an arrow with arrowheads on both left and right, used for ERO's
- `\implies` gives the standard implies symbol
- `\iff` gives the standard if and only if symbol
- `\union` gives the cup symbol
- `\intersect` gives the cap symbol
- `\product` and `cross` both give the x symbol for multiplication
- `\composed` gives a small circ, used for function composition

## Greek symbol changes
- `\epsilon` has been remapped to output `\varepsilon`

## Macros
Various macros have also been added

- `\comp{A}` is used to write A complement
- `f \restrictedto{(a,b)}`
- `\func{f}{A}{B}` is used to write the definition of a function f from A to B
- `\rfunc{f}` is used in a similar way to `\func` but for a function from a subset of R A to R
- `a \congr{b}{c}` is used to write a is congruent to b mod c
- `\dif{y}{x}` is used to write dy/dx in a fraction
- `\suminfty` gives a sum from n=1 to infinity

