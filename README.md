
<!-- README.md is generated from README.Rmd. Please edit that file -->

# sugarbag

[![Travis-CI Build
Status](https://travis-ci.org/srkobakian/sugarbag.svg?branch=master)](https://travis-ci.org/srkobakian/sugarbag)

The **sugarbag** package implements tesselated hexagon maps for
visualising geo-spatial data. Hexagons of equal size are positioned to
best preserve angles and minimise distance from their actual location.
This method provides an alternative to cartograms that allows regions of
all areas to be compared on the same scale without distortion.

Maps containing regions with a few small and densely populated areas are
extremely distorted in cartograms. An example of this is a population
cartogram of Australia, which distorts the map into an unrecognisable
shape. The technique implemented in this package is particularly useful
for these
regions.

<img src="man/figures/README-tas-anim-1.gif" width="100%" />

## Installation

<!-- You can install the released version of sugarbag from [CRAN](https://CRAN.R-project.org) with: -->

<!-- ``` r -->

<!-- install.packages("sugarbag") -->

<!-- ``` -->

You can install the development version from GitHub using

``` r
# install.packages("remotes")
remotes::install_github("srkobakian/sugarbag")
```

## Getting started

Refer to pkgdown site: <https://srkobakian.github.io/sugarbag/>
