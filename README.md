
<!-- README.md is generated from README.Rmd. Please edit that file -->

# cwdata

<!-- badges: start -->

[![R build
status](https://github.com/zyliu178/ETC5523Week7/workflows/R-CMD-check/badge.svg)](https://github.com/zyliu178/ETC5523Week7/actions)
<!-- badges: end -->

The goal of cwdata is to …

## Installation

You can install the released version of cwdata from
[CRAN](https://CRAN.R-project.org) with:

``` r
install.packages("cwdata")
```

And the development version from [GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("zyliu178/ETC5523Week7")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(cwdata)
library(tibble)
key_crop_yields
#> # A tibble: 13,075 x 15
#>    code   year wheat_tonnes_pe… rice_tonnes_per… maize_tonnes_pe…
#>    <chr> <dbl>            <dbl>            <dbl>            <dbl>
#>  1 AFG    1961            1.02              1.52             1.4 
#>  2 AFG    1962            0.974             1.52             1.4 
#>  3 AFG    1963            0.832             1.52             1.43
#>  4 AFG    1964            0.951             1.73             1.43
#>  5 AFG    1965            0.972             1.73             1.44
#>  6 AFG    1966            0.867             1.52             1.44
#>  7 AFG    1967            1.12              1.92             1.41
#>  8 AFG    1968            1.16              1.95             1.71
#>  9 AFG    1969            1.19              1.98             1.72
#> 10 AFG    1970            0.956             1.81             1.48
#> # … with 13,065 more rows, and 10 more variables:
#> #   soybeans_tonnes_per_hectare <dbl>, potatoes_tonnes_per_hectare <dbl>,
#> #   beans_tonnes_per_hectare <dbl>, peas_tonnes_per_hectare <dbl>,
#> #   cassava_tonnes_per_hectare <dbl>, barley_tonnes_per_hectare <dbl>,
#> #   cocoa_beans_tonnes_per_hectare <dbl>, bananas_tonnes_per_hectare <dbl>,
#> #   crop <chr>, tonnes_per_hectare <chr>
```
