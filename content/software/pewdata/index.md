---
author: Fred Solt & HU Yue
title: pewdata

categories:
- methodology
- data

date: "2021-04-08"
featured: true
draft: false

excerpt: An R package that provides reproducible, programmatic access to survey datasets from the [Pew Research Center](http://www.pewresearch.org).
layout: single

links:
- icon: home
  icon_pack: fas
  name: website
  url: https://cran.r-project.org/package=pewdata
- icon: github
  icon_pack: fab
  name: source
  url: https://github.com/fsolt/pewdata
---

<img src="featured-hex.png" width = "134.435" height = "155.25"  align="right" />

Solt, Frederick, **Yue Hu**, and Eric Persson. 2021. pewdata: Reproducible Retrieval of Pew Research Center Datasets. R package version 0.3.2. The Comprehensive R Archive Network (CRAN).

[![CRAN version](http://www.r-pkg.org/badges/version/pewdata)](https://cran.r-project.org/package=pewdata) 
![](http://cranlogs.r-pkg.org/badges/grand-total/pewdata) 
![](http://cranlogs.r-pkg.org/badges/pewdata?color=orange)

`pewdata` is an R package that provides reproducible, programmatic access to survey datasets from the [Pew Research Center](http://www.pewresearch.org).

To install:

* the latest released version: `install.packages("pewdata")`
* the latest development version: 

```R
if (!require(ghit)) install.packages("ghit")
ghit::install_github("fsolt/pewdata")
```
Note that `pewdata` depends on the Firefox browser; if you don't already have it installed on your machine, [get it here](https://www.mozilla.org/firefox).

For more details, check out [the vignette](https://cran.r-project.org/web/packages/pewdata/vignettes/pewdata-vignette.html).
