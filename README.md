# MCTrend
Monte Carlo time series trend analysis.

# Requirements
Dependencies:
  trend, reshape2, ggplot2, magrittr, lmomco, dplyr

# Installation
You can install the development version of **MCTrend** from GitHub with this R command:
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
```x``` | A data frame containing the input data. The first raw expected to contain model names or time series names. |
```n_rep``` | Number of replications for the Monte Carlo simulation. |
```plot_title``` | Title for the plot. |
```opt``` | A number indicating type of results, for opt = 1 returns test result, opt = 2 returns plot. |

# Reporting bugs
If you find an error in some function, want to report a typo in the documentation or submit a recommendation, you can do it [here](https://github.com/Alobondo/MCTrend/issues)

# Keywords
Hydrology, R package, Time Series, Monte-Carlo
