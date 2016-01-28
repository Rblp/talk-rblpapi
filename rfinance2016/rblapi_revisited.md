
### Rblapi Revisited: One Year Later

Abstract submitted in consideration for a lightning talk at _R/Finance 2016_

Dirk Eddelbuettel, Whit Armstrong, John Laing

One year ago we presented [Rblpapi](http://github.com/Rblp/Rblpapi). It
connects the R environment to the
[Bloomberg](http://www.bloomberg.com) system, data store, calculation engines
and more by utilizing both
[Rcpp](http://dirk.eddelbuettel.com/code/rcpp.html) and the [C++ API](http://www.bloomberglabs.com/api/) provided by Bloomberg.

In that original presentation, we stated that we did not expect immediate
availability on Windows as mixing C++ code from different compilers is orders
of magnitude harder than for C code, if not outright impossible.  To our
surprise, a splendid pull request arrived only a few weeks later implementing
just that: a basic Windows build. Along with some refactoring of the build
process and more polish, this seading to the [CRAN](http://cran.r-project.org)
publication of the package---and much wider exposure.

In this short talk, we plan to both highlight this unanticipated event and
other features added _by the community_ now that the package has this much
more visibility---and also briefly reflect on the benefits of open source
R packages for Finance with good visibility and suitable governance.
