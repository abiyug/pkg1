
<!-- README.md is generated from README.Rmd. Please edit that file -->
pkg1
====

<!-- badges: start -->
<!-- badges: end -->
The goal of pkg1 is to ...

Installation
------------

For support on this package go here:

URL: <http://github.com/abiyug/pkg1> BugReports: <https://github.com/abiyug/pkg1/issues>

And the development version from [GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("abiyug/pkg1")
```

Example
-------

This is a basic example which shows you how to solve a common problem:

``` r
library(pkg1)
## basic example code
```

What is special about using `README.Rmd` instead of just `README.md`? You can include R chunks like so:

``` r
summary(df_1)
#>       mpg             cyl         disp             hp             drat      
#>  Min.   :18.70   Min.   :4   Min.   :108.0   Min.   : 93.0   Min.   :3.080  
#>  1st Qu.:21.00   1st Qu.:6   1st Qu.:160.0   1st Qu.:110.0   1st Qu.:3.150  
#>  Median :21.00   Median :6   Median :160.0   Median :110.0   Median :3.850  
#>  Mean   :20.98   Mean   :6   Mean   :209.2   Mean   :119.6   Mean   :3.576  
#>  3rd Qu.:21.40   3rd Qu.:6   3rd Qu.:258.0   3rd Qu.:110.0   3rd Qu.:3.900  
#>  Max.   :22.80   Max.   :8   Max.   :360.0   Max.   :175.0   Max.   :3.900
```

You'll still need to render `README.Rmd` regularly, to keep `README.md` up-to-date.
