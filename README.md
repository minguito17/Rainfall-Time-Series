
# Australian Rainfall Forecasting

## Description / Overview

This project forecasts monthly rainfall patterns in major Australian cities (Darwin, Perth, Sydney, Melbourne) using time series models. The goal is to help stakeholders in agriculture, infrastructure, and disaster planning better prepare for climate risks and seasonal weather changes.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Contributing](#contributing)
- [License](#license)
- [Authors / Credits](#authors--credits)
- [Contact Information](#contact-information)
- [References / Acknowledgments](#references--acknowledgments)

## Installation

1. Clone the repository:  
   ```
   git clone https://github.com/Chutacos/RainfallTimeSeries.git
   cd RainfallTimeSeries
   ```
2. Install required R libraries:  
   Install packages like `dplyr`, `ggplot2`, `lubridate`, `fpp3`, `xgboost`, `forecast`, `caret`, and others as needed.

## Usage

- Load the data `weatherAUS.csv` and run the scripts provided.
- Use R scripts or notebooks to:
  - Clean and preprocess the data
  - Convert daily weather data into monthly summaries
  - Build and evaluate models: Linear Regression, ARIMA, and XGBoost
  - Generate time series plots, ACF/PACF, decomposition, and forecast accuracy tables.

## Features

- Forecasts rainfall for four major Australian cities.
- Uses multiple modeling approaches (Linear Regression, ARIMA, XGBoost).
- Handles stationarity checks, differencing, and decomposition.
- Provides visualizations for trends, seasonality, and residuals.
- Outputs forecast accuracy metrics (RMSE, MAE, MAPE).

## Contributing

Pull requests are welcome. Please open an issue first to discuss major changes.

## License

This project is for academic purposes only.

## Authors / Credits

- Marinela Inguito
- Robert Marriott
- Jose Guarneros Padilla

## Contact Information

- minguito@sandiego.edu

## References / Acknowledgments

- Australian Bureau of Meteorology dataset
- Alim et al. (2020). Comparison of ARIMA and XGBoost. BMJ Open.
- Hennessy et al. (1999). Trends in Australian Rainfall. CSIRO.
- King et al. (2014). Extreme Rainfall Variability in Australia. Journal of Climate.
