# Stock Data Analysis using R

## Overview
This project fetches stock data for selected companies using the `quantmod` package in R. It downloads historical stock prices from Yahoo Finance and stores them in a structured format for further analysis.

## Features
- Downloads stock data for multiple companies (AAPL, MSFT, GOOG)
- Handles errors gracefully if data retrieval fails
- Uses various R libraries for data analysis and visualization

## Prerequisites
Ensure you have R installed along with the following packages:

```r
install.packages(c("quantmod", "TTR", "PerformanceAnalytics", "ggplot2", "plotly", "leaflet", "knitr", "DT", "broom", "shiny"))
```

## How to Use
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/your-repository.git
   cd your-repository
   ```
2. Open R or RStudio and run the script to fetch stock data:
   ```r
   source("your_script.R")
   ```

## Code Explanation
- Defines a list of stock symbols (`AAPL`, `MSFT`, `GOOG`)
- Sets the date range for data extraction
- Uses `getSymbols()` from `quantmod` to download data from Yahoo Finance
- Implements error handling with `tryCatch()` to ensure smooth execution

## Dependencies
This script depends on the following R libraries:
- `quantmod`: Fetches financial data
- `TTR`: Provides technical trading tools
- `PerformanceAnalytics`: Financial performance analysis
- `ggplot2`: Visualization
- `plotly`: Interactive plots
- `leaflet`: Mapping (if needed)
- `knitr`: Report generation
- `DT`: Interactive tables
- `broom`: Tidying models
- `shiny`: Web application framework for R

## Upcoming Improvements
- Implementation of **Linear Regression** for stock trend analysis
- Conducting **T-tests** for statistical comparisons
- Enhancing **interactive plots** with additional insights
- Developing a **Shiny UI** for a web-based interactive dashboard

## License
This project is licensed under the MIT License.

## Author
Sumit mishra - https://github.com/sumitm896

