
<!-- README.md is generated from README.Rmd. Please edit that file -->
actstatr: Interactive R tutorials for actuarial statistics
==========================================================

actstatr is an R package bundling several [learnr](https://rstudio.github.io/learnr/index.html) interactive tutorials for actuarial statistics. These tutorials consist of content along with interactive components for checking and reinforcing understanding. Tutorial topics include (tutorial name in parentheses):

-   Basics of R (basicr): An introduction to the basic capabilities of the `R` software.
-   Life Tables (lifetables): Implementation of life table computations using the package `lifecontingencies`.

Installation:
=============

To install the latest development version:

``` r
    install.packages("devtools")
    devtools::install_github("amvillegas/actstatr")
```

Running a tutorial
==================

To run a tutorial use the following code

``` r
    install.packages("learnr")
    learnr::run_tutorial("basicr", package = "actstatr")
```
