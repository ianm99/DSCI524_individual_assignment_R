
<!-- README.md is generated from README.Rmd. Please edit that file -->

# regexcite

<!-- badges: start -->
<!-- badges: end -->

The goal of regexcite is to provide some useful functions fo routine
string manipulations

## Installation

You can install the development version of regexcite from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("ianm99/DSCI524_individual_assignment_R")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(regexcite)

(x <- "alfa,bravo,charlie,delta")
#> [1] "alfa,bravo,charlie,delta"
str_split_one(x, pattern = ",")
#> [1] "alfa"    "bravo"   "charlie" "delta"
```
