
<!-- README.md is generated from README.Rmd. Please edit that file -->
praiseme
========

The goal of praiseme is to deliver some lovely praise.

Installation
------------

You can install praiseme from github with:

``` r
# install.packages("devtools")
devtools::install_github("Thilaksha/praiseme")
```

Example
-------

This is a basic example which shows you how to solve a common problem:

``` r
## Just you
library(praiseme)
praise()
#> [1] "You are the best, Thilaksha"

# Or a friend
praise("Maddy!")
#> [1] "You are the best, Maddy!"
```
