# scDiagnostics: diagnostic functions to assess the quality of cell type annotations in single-cell RNA-seq data

# Overview

The accurate annotation of cell types is a critical step in single-cell RNA-sequencing (scRNA-seq) analysis. While annotation transfer from a reference dataset offers a convenient and automated approach, it can also introduce biases and errors if not performed carefully.

**`scDiagnostics`** is an R package designed to address this challenge by providing a comprehensive set of diagnostic tools for evaluating the quality of cell type annotations in scRNA-seq data. With **`scDiagnostics`**, researchers can systematically assess the compatibility and accuracy of annotations, ensuring reliable and reproducible results in their scRNA-seq analysis workflow.

# Workshop Materials

This repository contains the workshop materials. You may find the PDF slides in `inst/slides` which contain an overview of the role of the **`scDiagnostics`** package in cell type annotation. You may find the fully documented workshop code examples in the `vignettes` folder. The workshop Docker image is also publicly available [here](https://github.com/anthonychristidis/scDiagnosticsBioc2024Demo/pkgs/container/scdiagnosticsbioc2024demo).

# Installation

To install the development version of the **`scDiagnostics`** from GitHub use the following command:

``` r
devtools::install_github("ccb-hms/scDiagnostics")
```

NOTE: you will need the [remotes](https://cran.r-project.org/web/packages/remotes/index.html) package to install from GitHub.

To build the **`scDiagnostics`** package vignettes upon installation use:

``` r
devtools::install_github("ccb-hms/scDiagnostics",
                         build_vignettes = TRUE,
                         dependencies = TRUE)
```

# Usage

To get a complete overview of the functionality of the package, refer to the [pkgdown website](https://ccb-hms.github.io/scDiagnostics/index.html) for code examples. The complete documentation of each available function in **`scDiagnostics`**, which includes implementation details and working examples, is available in the [reference tab](https://ccb-hms.github.io/scDiagnostics/reference/index.html).

**`scDiagnostics`** is designed to be user-friendly and integrates seamlessly into any scRNA-seq analysis workflow. By providing robust diagnostic tools, the package helps ensure the accuracy and reliability of cell type annotations, leading to more meaningful and reproducible results.