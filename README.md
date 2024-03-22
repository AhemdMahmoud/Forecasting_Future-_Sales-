# Forecasting Future Sales 

## This project is an exploration of Sales market data using `time series analysis techniques` `(ARIMA, SARMA)`. In this analysis, we aim to gain insights into the historical performance of Sales, identify patterns, and potentially make predictions about future trends.

![Sales Image](https://github.com/AhemdMahmoud/Stock_TS/blob/main/download.png)

# Just want to quickly look at some notebooks, without executing any code?
## <a href="https://nbviewer.org/github/AhemdMahmoud/Forecasting_Future-_Sales-/blob/main/Forcasting.ipynb"><img src="https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg" alt="Render nbviewer" /></a>  Or  Edit [open Colab](https://colab.research.google.com/drive/1VeTbkC6uroN5LwjyNQQ5eOc7PKyoSqqn#scrollTo=aujTf2zZIasd)


## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Methods](#methods)
- [Results](#results)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

# Introduction

## Sales market data is rich in information and presents a challenging yet rewarding environment for analysis. Time series analysis provides powerful tools to understand the dynamics of sales over time. In this project, we employ various time series analysis techniques to explore historical sales data and extract meaningful insights.

## Dataset

### The dataset used in this project consists of historical sales data. It includes monthly opening, closing, high, and low sales, as well as other relevant metrics over a specified period.
* ##  Sample
| Month       | Sales   |
|-------------|---------|
| 1964-01-01  | 2815.0  |
| 1964-02-01  | 2672.0  |
| 1964-03-01  | 2755.0  |
| 1964-04-01  | 2721.0  |
| 1964-05-01  | 2946.0  |

## Methods

### We utilize several time series analysis techniques, including but not limited to:

- **Exploratory Data Analysis (EDA):** Initial exploration of the dataset to understand its structure, trends, and anomalies.
- **Statistical Analysis:** Applying statistical tests and metrics to analyze the distribution, volatility, and other characteristics of sales data.
- **Time Series Decomposition:** Decomposing the time series into its constituent components (trend, seasonality, and noise) to better understand underlying patterns.
- **Forecasting:** Using models such as ARIMA (AutoRegressive Integrated Moving Average) and SARMA for predicting future sales trends.
- **Correlation Analysis:** Investigating the relationships between different sales metrics or market factors to identify potential dependencies and opportunities for optimization.

# Results

### Our analysis yields the following insights:
- Visualize the Time Series Data
- Make the time series data stationary
- Plot the Correlation and AutoCorrelation Charts
- Construct the ARIMA Model or Seasonal ARIMA based on the data
- Use the model to make predictions



## Usage

To use this project:

1. Clone the repository: `git clone https://github.com/AhemdMahmoud/Sales_TS.git`

## Contributing

Contributions to this project are welcome. If you have suggestions for improvements, bug fixes, or additional analysis techniques, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
