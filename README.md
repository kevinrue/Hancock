<!-- badges: start -->
[![R build status](https://github.com/kevinrue/hancock/workflows/R-CMD-check/badge.svg)](https://github.com/kevinrue/hancock/actions)
[![Travis build status](https://travis-ci.org/kevinrue/hancock.svg?branch=master)](https://travis-ci.org/kevinrue/hancock)
[![Coverage status](https://codecov.io/gh/kevinrue/hancock/branch/master/graph/badge.svg)](https://codecov.io/github/kevinrue/hancock?branch=master)
<!-- badges: end -->

# hancock <img src="man/figures/logo.png" align="right" width="120"/>

The goal of the [_hancock_](https://github.com/kevinrue/hancock) package is to provide a collection of methods for learning and applying gene signatures associated with cellular phenotypes and identities.
Particular focus is given to single-cell data stored in objects derived from the [`SummarizedExperiment`](https://bioconductor.org/packages/release/bioc/html/SummarizedExperiment.html) class.

# Prerequisites

The [_hancock_](https://github.com/kevinrue/hancock) package supports classes of gene sets defined in multiple packages.
However, it uses `BaseSets` classes defined in the [_unisets_](https://github.com/kevinrue/unisets) package to return newly learned signatures with accompanying metadata.
This dependency may be installed as follows:

```
install.packages("devtools")
devtools::install_github("kevinrue/unisets", build_opts = c("--no-resave-data", "--no-manual"))
```

Several functions support the `tbl_geneset` class defined in the [_GeneSet_](https://github.com/Kayla-Morrell/GeneSet) package.
This package may be installed as follows:

```
devtools::install_github("Kayla-Morrell/GeneSet")
```

# Installation

The [_hancock_](https://github.com/kevinrue/hancock) package may be installed as follows:

```
install.packages("devtools")
devtools::install_github("kevinrue/hancock")
```

To build the vignette as well, please use the following code:

```
devtools::install_github("kevinrue/hancock", build_opts = c("--no-resave-data", "--no-manual"))
```

# Usage

Demonstration notebooks are available as vignettes and on the companion repository: https://github.com/kevinrue/hancock2018

# Contributing

Considerate contributions are very welcome!
Please refer to the [contributing guidelines](CONTRIBUTING.md) for more details.
