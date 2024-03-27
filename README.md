# MCTrend <img src="man/figures/MC_Trend_logo.png" align="right" width="360px" height="390px" />
Monte Carlo time series trend analysis.
Based on: Ricchetti, (2018) <https://repositorio.uchile.cl/handle/2250/168487>
# Requirements
Dependencies:
  trend, reshape2, ggplot2, magrittr, lmomco, dplyr

# Installation
You can install the currently-released version of **MCTrend** from CRAN with this R command:
```
install.packages("MCTrend")
```
Alternatively, you can install the development version from GitHub with:
```
# install.packages("remotes")
remotes::install_github("Alobondo/MCTrend")
library(MCTrend)
```

# Usage
Functions | Description |
--- | --- |
```MCTrend()``` | Apply the Monte Carlo Trend test to hydrological time series. |

Parameters | Description |
--- | --- |
```x``` | A data frame containing the input data. The first row expected to contain model or time series names. First column from left should have time/date data. |
```n_rep``` | Number of replications for the Monte Carlo simulation (n_rep > 4). |
```plot_title``` | Title for the plot. |
```int``` | Number indicating lower threshold value of the interval within which no trend is defined, the upper value is calculated based on this value, by default a lower value of 0.25 is considered. |
```opt``` | A number indicating type of results, for opt = 1 returns test result, opt = 2 returns plot. |

# File for example
To download a file with the reference format follow this path: https://rb.gy/4jfqk

# Reporting bugs
If you find an error in any function, want to report a typo in the documentation or submit a recommendation, you can do it [here](https://github.com/Alobondo/MCTrend/issues)

# Keywords
Hydrology, R package, Time Series, Monte-Carlo
