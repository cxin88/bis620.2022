
<!-- README.md is generated from README.Rmd. Please edit that file -->

# bis620.2022

[![R-CMD-check](https://github.com/cxin88/bis620.2022/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/cxin88/bis620.2022/actions/workflows/R-CMD-check.yaml)
[![lint](https://github.com/cxin88/bis620.2022/actions/workflows/lint.yaml/badge.svg)](https://github.com/cxin88/bis620.2022/actions/workflows/lint.yaml)
[![test-coverage](https://github.com/cxin88/bis620.2022/actions/workflows/test-coverage.yaml/badge.svg)](https://github.com/cxin88/bis620.2022/actions/workflows/test-coverage.yaml)

## Installation

You can install the development version of bis620.2022 from
[GitHub](https://github.com/cxin88/bis620.2022) with: <br>
`install.packages("devtools")` <br>
`devtools::install_github("cxin88/bis620.2022")`

## Example

``` r
library('usethis')
library('devtools')
document()
#> ℹ Updating bis620.2022 documentation
#> ℹ Loading bis620.2022
library('bis620.2022')
## basic example code
data(ukb_accel)
ukb_accel[1:1000, ] |>
      spectral_signature() |>
      accel_plot()
```

<img src="man/figures/README-example-1.png" width="100%" />
