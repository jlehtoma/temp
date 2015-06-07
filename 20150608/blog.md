

rOpenGov is all about reproducible research, so preparing a
**reproducible poster** became our mission after having the chance to
present at [International Conference on Computational Social Science
(ICCSS 2015)](http://iccss2015.eu/index.html) in Helsinki, June 8-11,
2015 (poster .. at Monday poster session 15:30-17:00 for those who are
attending the event).

Our poster includes the title field, coloured text boxes,
automatically numbered references, R code and output figures. Running
the poster source code downloads data with the [eurostat R
package](http://github.com/rOpenGov/eurostat/) and generates the
poster figures. We achieved this with a combination of
[LaTeX]()/[tikz](), and [R](http://www.r-project.org)/[Sweave](). The
LaTeX/tikz combination allows reproducible design of arbitrary poster
layouts and schematic figures, as well as automated numbering of
figures and references. The R/Sweave allows incorporating R code and
output (figures, tables, text). The [a0poster style]() provides
appropriate font sizes and other LaTeX utilities for posters. If you
are a frequent LaTeX user, we also warmly recommend familiarizing with
[tikz](). For details, see the [poster
sources](https://github.com/rOpenGov/poster/blob/master/2015-ICCSS/poster.Rnw).
To reproduce the poster, run
https://github.com/rOpenGov/poster/blob/master/2015-ICCSS/poster.Rnw.

See the poster at ...

We ended up using plain tikz for designing the poster layout, although
nice ready-made poster layouts are also provided by [baposter]() and
[](). Whereas the ready-made layouts are useful for fast poster
design, they also limit the available options as the graphical
elements are laid out as tightly defined text boxes, which is not
suitable for all purposes, and mixing ready-made styles with free
design is potentially confusing. With []() we could not include R
code, either.
