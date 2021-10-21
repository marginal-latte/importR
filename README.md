# importR

![](vacuum.png)

The goal of importR is to create an R data frame from external data in
SAS, SPSS, or Stata binary files, Excel Workbooks, or delimited text files.

## Installation

You can install the released version of importR from [CRAN](https://CRAN.R-project.org) with:

``` r
if(!require("remotes"")){
  install.packages("remotes")
  library(remotes)
}

remotes::install_github("importR")
```

## Example

You can import data file using

``` r
library(importR)
mydata <- import()
```

