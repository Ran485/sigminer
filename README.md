
<!-- README.md is generated from README.Rmd. Please edit that file -->
sigminer
========

<img src="https://github.com/ShixiangWang/sigminer/blob/master/inst/figures/sigminer.png" height="200" align="right" />

[![CRAN status](https://www.r-pkg.org/badges/version/sigminer)](https://cran.r-project.org/package=sigminer) [![lifecycle](https://img.shields.io/badge/lifecycle-maturing-blue.svg)](https://www.tidyverse.org/lifecycle/#maturing) [![AppVeyor build status](https://ci.appveyor.com/api/projects/status/github/ShixiangWang/sigminer?branch=master&svg=true)](https://ci.appveyor.com/project/ShixiangWang/sigminer) [![Travis build status](https://travis-ci.org/ShixiangWang/sigminer.svg?branch=master)](https://travis-ci.org/ShixiangWang/sigminer) [![Coverage status](https://codecov.io/gh/ShixiangWang/sigminer/branch/master/graph/badge.svg)](https://codecov.io/github/ShixiangWang/sigminer?branch=master)

The goal of **sigminer** is to provide an uniform interface for genomic variation signature analysis and visualization. **sigminer** is originated from [VSHunter](https://github.com/ShixiangWang/VSHunter) package I wrote. I hate ugly structure and function names in VSHunter, thus reconstruct it using concise function names, S4 classes and S3 methods etc.. I will continue to add more features to uncover genomic variation signatures and their correlationship with phenotyes and genotypes.

**sigminer** is powered by [NMF](https://github.com/renozao/NMF) package and [maftools](https://github.com/PoisonAlien/maftools) package.

Installation
------------

You can install the development version of sigminer from Github with:

``` r
devtools::install_github("ShixiangWang/sigminer")
```

Citation
--------

-   *Macintyre, Geoff, et al. “Copy number signatures and mutational processes in ovarian carcinoma.” Nature genetics 50.9 (2018): 1262.*

-   *Wang, Shixiang, et al. “APOBEC3B and APOBEC mutational signature as potential predictive markers for immunotherapy response in non-small cell lung cancer.” Oncogene (2018).*

TODO
----

-   survival analysis, including
-   Cox
-   KM