Bro Cheat Sheet
===============

This repository features the official Bro language cheat sheet, which
succinctly summarizes the key components of the Bro scripting language and
describes the built-in functions (BiFs).

Tweaking
--------
It turns out that Bro provides more features than we could fit on single
double-sided sheet. Particularly the documentation of all BiFs consumes a lot
of space, although we only selected a subset of functions that we deem relevant
for the majority of users. Still, there exist folks who may want a complete
"desktop reference" rather than a succinct cheat sheet. If you prefer to have
*all* BiFs included on the cheat sheet, download the LaTeX source and uncomment
the line

    %\verbosetrue

at the beginning of the file. Then use your favorite LaTeX compiler (e.g.,
`pdflatex`) to build the verbose version of the cheat sheet with additional,
more low-level BiFs. However, we emphasize that you will *not* need these extra
BiFs in 99% of your scripting experience, because they are either extremely
rarely used or already wrapped behind more accessible interfaces in the base
scripts.

License
-------

This work is licensed under the
**Creative Commons Attribution-NonCommercial-ShareAlike 3.0 Unported**
license. Please see the file COPYING for more information.

Screenshots
-----------

Below are two screenshots of the cheat sheet.

![Page 1](https://github.com/bro/cheat-sheet/raw/master/figs/shot-main.png)

![Page 2](https://github.com/bro/cheat-sheet/raw/master/figs/shot-bif.png)
