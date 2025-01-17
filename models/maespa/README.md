
# PEcAn.MAESPA

<!-- badges: start -->

[![Lifecycle: experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://lifecycle.r-lib.org/articles/stages.html#experimental)
[![PEcAn.MAESPA status badge](https://pecanproject.r-universe.dev/badges/PEcAn.MAESPA)](https://pecanproject.r-universe.dev/PEcAn.MAESPA)

<!-- badges: end -->

PEcAn Functions Used for Ecological Forecasts and Reanalysis using MAESPA

## Installation

You can install the development version of `PEcAn.MAESPA` from r-universe like so:

``` r
# Enable repository from pecanproject
options(repos = c(
  pecanproject = 'https://pecanproject.r-universe.dev',
  CRAN = 'https://cloud.r-project.org'))
# Download and install PEcAn.MAESPA in R
install.packages('PEcAn.MAESPA')
```

Or you can install directly from GitHub with the remotes package like so:

``` r
library(remotes)
install_github('pecanproject/pecan',  subdir = "models/maespa")
```

## Example

This is a basic example which shows you how to solve a common problem:

```r
library(PEcAn.MAESPA)
## basic example code
```

