
<!-- README.md is generated from README.Rmd. Please edit that file -->

# ecorisk <img src="man/figures/ecorisk_logo.png" alt="ecorisk logo" align="right" width="100" height="112"/>

<!-- badges: start -->

[![CRAN
status](https://www.r-pkg.org/badges/version/ecorisk)](https://cran.r-project.org/package=ecorisk)
[![R-CMD-check](https://github.com/HeleneGutte/ecorisk/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/HeleneGutte/ecorisk/actions/workflows/R-CMD-check.yaml)
[![CRAN downloads
total](https://cranlogs.r-pkg.org/badges/grand-total/ecorisk)](https://cran.r-project.org/package=ecorisk)
[![License:
MIT](https://img.shields.io/badge/license-MIT-blue)](LICENSE)
[![DOI](https://img.shields.io/badge/DOI-10.1016%2Fj.softx.2026.102612-blue)](https://doi.org/10.1016/j.softx.2026.102612)
<!-- badges: end -->

## Overview

*ecorisk* is an R package operationalizing a modular risk assessment
framework for ecosystem-based management. It supports semiquantitative
expert scoring approaches as well as quantitative time-series analysis —
and allows both to be combined in one integrated assessment.

Key features:

- Risk assessments from single indicator–pressure combinations up to
  full ecosystem scale
- Integration of expert knowledge and time-series modelling in one
  framework
- Explicit uncertainty assessment throughout all steps
- Applicable to marine and terrestrial ecosystems
- Publication-ready visualizations via `plot_radar()` and
  `plot_heatmap()`

The *ecorisk* workflow consists of two parallel pathways (expert scoring
and modelling) that are joined for vulnerability and risk calculation,
and can then be aggregated to multi-pressure, multi-indicator, and
ecosystem risk scores:

<img src="man/figures/Figure1_workflow.png" alt="Workflow of the ecorisk package" width="80%"/>

## Installation

Install the released version from CRAN:

``` r
install.packages("ecorisk")
```

Or install the development version from GitHub using the `pak` package:

``` r
# install.packages("pak")
pak::pak("HeleneGutte/ecorisk")
```

## Usage

A full tutorial using the provided demo datasets is available in the
package vignette:

``` r
vignette("ecorisk")
```

Further background on the risk assessment framework and step-by-step
function documentation are available on the [package
website](https://helenegutte.github.io/ecorisk/).

## Citation

If you use the *ecorisk* package, please cite it using:

``` r
citation("ecorisk")
#> To cite package 'ecorisk' in publications use:
#> 
#>   Gutte H, Otto S (2026). _ecorisk: Risk Assessments for Ecosystems or
#>   Ecosystem Components_. R package version 0.3.1,
#>   <https://github.com/HeleneGutte/ecorisk>.
#> 
#> A BibTeX entry for LaTeX users is
#> 
#>   @Manual{,
#>     title = {ecorisk: Risk Assessments for Ecosystems or Ecosystem Components},
#>     author = {Helene Gutte and Saskia A. Otto},
#>     year = {2026},
#>     note = {R package version 0.3.1},
#>     url = {https://github.com/HeleneGutte/ecorisk},
#>   }
```

If you use the *ecorisk* framework or methodology, please also cite the
accompanying software paper:

> Gutte, H.M., Möllmann, C. & Otto, S.A. (2026). ecorisk: A modular R
> tool for ecological risk assessment analysis. *SoftwareX*, 34, 102612.
> <https://doi.org/10.1016/j.softx.2026.102612>
