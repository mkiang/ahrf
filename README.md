
<!-- README.md is generated from README.Rmd. Please edit that file -->
About
=====

This repo contains R scripts (in the [`data-raw` folder](https://github.com/jjchern/ahrf/tree/master/data-raw)) that download county-level and state-level [Area Health Resources Files (AHRF)](http://ahrf.hrsa.gov/download.htm). The datasets are stored in the [`data` folder](https://github.com/jjchern/ahrf/tree/master/data).

AHRF is issued annually. The most recent release is in 2015 (as of May 5, 2016).

Installation
============

You can also download the datasets as an R package. The size of `ahrf_county.rda` is 16.7M, so it might take a while to install and load into memory.

``` r
# install.packages("devtools")
devtools::install_github("jjchern/hospitals")

# To uninstall the package, use:
# remove.packages("hospitals")
```
