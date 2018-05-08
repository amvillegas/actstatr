
<!-- README.md is generated from README.Rmd. Please edit that file -->
actstatr: Interactive R tutorials for actuarial statistics
==========================================================

actstatr is an R package bundling several [learnr](https://rstudio.github.io/learnr/index.html) interactive tutorials for actuarial statistics. These tutorials consist of content along with interactive components for checking and reinforcing understanding. Tutorial topics include (tutorial name in parentheses):

-   Basics of R (`"basicr"`): An introduction to the basic capabilities of the `R` software.
-   Life Tables (`"lifetables"`): Implementation of life table computations using the package `lifecontingencies`.
-   Survival analysis (`"survival"`): Survival analysis in `R`, including the Kaplan-Meier and Nelson-Aelen estimators, Cox regression models and accelerated failure time models.
-   Markov chains (`"markovchains"`): Application of continuous time Markov chains (MC) in `R` by using the package `markovchain`.
-   Mortality graduation (`"graduation"`): Implementation in `R` of mortality graduation techniques and of statistical tests to assess the adherence of a graduation.
-   Stochastic Mortality Models ("stochasticmortality"): Implementation in `R` of stochastic mortaity projections models using the package `StMoMo`.

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

where the first argument is the name of the tutorial. Available tutorials are: `"basicr"`, `"lifetables"`, `"survival"`, `"markovchains"`, `"graduation"`, `"stochasticmortality`.
