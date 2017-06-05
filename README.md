
<!-- README.md is generated from README.Rmd. Please edit that file -->
olsrr
=====

[![CRAN\_Status\_Badge](http://www.r-pkg.org/badges/version/olsrr)](https://cran.r-project.org/package=olsrr) [![Travis-CI Build Status](https://travis-ci.org/rsquaredacademy/olsrr.svg?branch=master)](https://travis-ci.org/rsquaredacademy/olsrr) [![AppVeyor Build Status](https://ci.appveyor.com/api/projects/status/github/rsquaredacademy/olsrr?branch=master&svg=true)](https://ci.appveyor.com/project/rsquaredacademy/olsrr) [![](https://cranlogs.r-pkg.org/badges/grand-total/olsrr)](https://cran.r-project.org/package=olsrr)

Overview
--------

The olsrr package provides following tools for teaching and learning OLS regression using R:

-   Comprehensive Regression Output

-   Variable Selection Procedures
    -   All Possible Regression
    -   Best Subsets Regression
    -   Stepwise Regression
    -   Stepwise Forward Regression
    -   Stepwise Backward Regression
    -   stepAIC Regression
    -   stepAIC Forward Regression
    -   stepAIC Backward Regression
-   Heteroskedasticity Tests
    -   Bartlett Test
    -   Breusch Pagan Test
    -   F Test
    -   Score Test
-   Collinearity Diagnostics
    -   Variance Inflation Factors
    -   Tolerance
    -   Eigenvalues
    -   Condition Indices
-   Model Fit Assessment
    -   Residual Fit Spread Plot
    -   Part & Partial Correlations
    -   Observed vs Fitted Values Plot
    -   Lack of Fit F Test
    -   Diagnostics Panel
-   Measures of Influence
    -   Cook's D Bar Plot
    -   Cook's D Chart
    -   DFBETAs Panel
    -   DFFITS Plot
    -   Studentized Residual Plot
    -   Standardized Residual Chart
    -   Studentized Residuals vs Leverage Plot
    -   Deleted Studentized Residuals vs Fitted Values Plot
    -   Hadi Plot
    -   Potential Residual Plot
-   Residual Diagnostics
    -   Residual QQ Plot
    -   Residual Histogram
    -   Residual Box Plot
    -   Residual Normality Test
    -   Residual vs Fitted Values Plot
-   Variable Contribution Assessment
    -   Residual vs Regressor Plot
    -   Added Variable Plot
    -   Residual Plus Component Plot

Installation
------------

You can install olsrr from github with:

``` r
# install olsrr from CRAN
install.packages("olsrr")

# the development version from github
# install.packages("devtools")
devtools::install_github("rsquaredacademy/olsrr")
```

Please note that this project is released with a [Contributor Code of Conduct](CONDUCT.md). By participating in this project you agree to abide by its terms.
