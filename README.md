
# BSSD

<!-- badges: start -->
<!-- badges: end -->

The goal of BSSD is to use Baysian smoothing spine method with dependence structure to estimate the trend of a series with seasonal effect.

## Installation

You can install the development version of BSSD like so:

``` r
install_github("benqzh/BSSD")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(BSSD)
## basic example code
BSSD(y,Ty=12,n.s=10^4,c=50,rho.p=1,e2b=1e-10,r=1,k=2,const0=1,uv=FALSE)
```

