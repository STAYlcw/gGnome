[![R-CMD-check](https://github.com/zining01/gGnome/actions/workflows/check-release.yaml/badge.svg)](https://github.com/zining01/gGnome/actions/workflows/check-release.yaml)
[![codecov.io](https://img.shields.io/codecov/c/github/mskilab/gGnome.svg)](https://codecov.io/github/mskilab/gGnome?branch=master)

# gGnome

```
            █████████                                             
           ███░░░░░███                                            
  ███████ ███     ░░░ ████████    ██████  █████████████    ██████ 
 ███░░███░███        ░░███░░███  ███░░███░░███░░███░░███  ███░░███
░███ ░███░███    █████░███ ░███ ░███ ░███ ░███ ░███ ░███ ░███████ 
░███ ░███░░███  ░░███ ░███ ░███ ░███ ░███ ░███ ░███ ░███ ░███░░░  
░░███████ ░░█████████ ████ █████░░██████  █████░███ █████░░██████ 
 ░░░░░███  ░░░░░░░░░ ░░░░ ░░░░░  ░░░░░░  ░░░░░ ░░░ ░░░░░  ░░░░░░  
 ███ ░███                                                         
░░██████                                                          
 ░░░░░░                                                           
```

**R API for genome graphs**

The **gGnome** package provides a flexible, queriable `R` interface to graphs
and walks of reference genomic intervals.  **gGnome** is written in the `R6` object
oriented standard and built around a powerful `GenomicRanges`, `data.table`, and
`igraph` backend, and thus supports agile interaction with graphs consisting of
hundreds of thousands of nodes and edges.  

## Install

1. Install R-3.6 or up

2. Install devtools

```{r}
install.packages('devtools')
install.packages('testthat')
```
3. Install gGnome and dependent packages

```{r}
## allows dependencies that throw warnings to install
Sys.setenv(R_REMOTES_NO_ERRORS_FROM_WARNINGS = TRUE)


devtools::install_github('STAYlcw/gGnome')
```


Documentation 
------------

[gGnome Tutorial](http://mskilab.com/gGnome/tutorial.html)

[alttext](https://github.com/mskilab/gGnome/articles/gGnome.png)

[PkgDown Site](https://tanubrata.github.io/gGnome/index.html)

<!---
[gGnome Developer Reference](docs/reference.md)
-->

<div id="attributions"/>

Attributions
------------
> Marcin Imieliński - Associate Professor, Weill Cornell Medicine
> Core Member, New York Genome Center.

> Xiaotong Yao - (as) Graduate Research Assistant, Weill Cornell Medicine, New York
> Genome Center.

> Zi-Ning Choo - Graduate Research Assistant, Weill Cornell Medicine, New York
> Genome Center.

> Alon Shaiber - Genomics Data Scientist, Weill Cornell Medicine, New York
> Genome Center.

> Joseph DeRose - (as) Undergraduate Research Assistant, New York Genome Center.

> Rick Mortensen - (as) Undergraduate Research Assistant, New York Genome Center,
> Memorial Sloan-Kettering Cancer Center

> Max Chao - Bioinformatic Analyst, Weill Cornell Medicine, New York Genome
> Center

Funding sources
------------

<img
src="https://static1.squarespace.com/static/562537a8e4b0bbf0e0b819f1/5ad81984575d1f7d69517350/5ad819f02b6a28750f79597c/1524111879079/DDCF.jpeg?format=1500w"
height="150" class ="center"> <img
src="https://static1.squarespace.com/static/562537a8e4b0bbf0e0b819f1/5ad81984575d1f7d69517350/5ad819b8aa4a996c2d584594/1524111841815/BWF.png?format=500w"
height="150" class ="center">




```
