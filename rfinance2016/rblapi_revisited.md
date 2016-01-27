
### Rblapi Revisited: One Year Later

Abstract submitted in consideration for _R/Finance 2016_

Dirk Eddelbuettel, Whit Armstring, John Laing

One year ago we presented Rblpapi. It connects the R environment to the
Bloomberg system, data store, calculation engines and more by utilizing both
Rcpp and C++ API provided by Bloomberg.

We stated that we did not expect immediate availability on Windows (as
missing C++ code from different compilers is orders of magnitude harder than
for C code, if not outright impossible).  To our surprise, a splendid pull
request arrived a few weeks later, permitting some refactoring of the build
process leading to the CRAN publication of the package.

In this short talk, we plan to both highlight this unanticipated event and
other features added _by the community_ now that the package has this much
more visibility---and also briefly reflect on the benefits of open source
packages with good visibility and suitable governance.
