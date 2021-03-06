
# fftw3

> FFTW, the Discrete Fourier Transform Library

[![Project Status: WIP - Initial development is in progress, but there has not yet been a stable, usable release suitable for the public.](http://www.repostatus.org/badges/latest/wip.svg)](http://www.repostatus.org/#wip)
[![Linux Build Status](https://travis-ci.org/MangoTheCat/fftw3.svg?branch=master)](https://travis-ci.org/MangoTheCat/fftw3)
[![Windows Build status](https://ci.appveyor.com/api/projects/status/github/MangoTheCat/fftw3?svg=true)](https://ci.appveyor.com/project/MangoTheCat/fftw3)
[![](http://www.r-pkg.org/badges/version/fftw3)](http://www.r-pkg.org/pkg/fftw3)
[![CRAN RStudio mirror downloads](http://cranlogs.r-pkg.org/badges/fftw3)](http://www.r-pkg.org/pkg/fftw3)


FFTW is a C subroutine library for computing the discrete Fourier transform (DFT) in one or more dimensions, of arbitrary input size, and of both real and complex data (as well as of even/odd data, i.e. the discrete cosine/sine transforms or DCT/DST). We believe that FFTW, which is free software, should become the FFT library of choice for most applications.

## Installation

```r
devtools::install_github("mangothecat/fftw3")
```

## Usage

```r
library(fftw3)
```

## License

GPL-3 © Matteo Frigo, Steven G. Johnson, Stefan Kral, IBM Austin Research Lab, CodeSourcery, Inc
