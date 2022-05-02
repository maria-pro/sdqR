
<!-- README.md is generated from README.Rmd. Please edit that file -->

# Strength and Diffuculties Questionnaire for R

<!-- badges: start -->
<!-- badges: end -->

The goal of sdqR is to provide access to one of the widely used
questionnaires, Strength and Difficulties Questionnaire. It provides
access to the questionnaire itself, includes several datasets for public
use of data analysis and exploration as well as provide some means to
use the questionnaire and datasets.

Currently, the package includes the following datasets:

To start using the packages, install the package using

``` r
#install package
remotes::install_github("maria-pro/sdqR", build_vignettes = TRUE)
#> Skipping install of 'sdqR' from a github remote, the SHA1 (cec8c7ac) has not changed since last install.
#>   Use `force = TRUE` to force installation
library(sdqR)
```

To load a dataset, use e.g.

``` r
data<-sdq_lsac
```

## Installation - to be completed once it is on CRAN

You can install the released version of sdqR from
[CRAN](https://CRAN.R-project.org) with:

``` r
#TO BE DONE
install.packages("sdqR")
```

And the development version from [GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("maria-pro/sdqR")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(sdqR)
## basic example code
```
