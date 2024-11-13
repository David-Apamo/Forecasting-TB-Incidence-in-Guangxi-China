# Forecasting-TB-Incidence-in-Guangxi-China
This repository contains files for TB Incidence forecasting using Seasonal ARIMA model and Prophet. The data for this analysis was obtained online from an article by Zheng et al., 2020, tiltled *"Statistical methods for predicting tuberculosis incidence based on data from Guangxi, China."* The article was published by BMC Infectious Diseases.

## Contents

* Data Preprocessing: Cleaning and preparing time series data for analysis.
* Visualization: Plotting trends, seasonality, and forecasted values to illustrate insights.
* Modeling: Building Seasonal ARIMA and Prophet models for forecasting, and performing model diagnostics to check if model assumptions hold.
* Forecasting: Predicting future TB incidence based on historical trends.

## Results

Seasonal ARIMA performed best with a validation RMSE value of 0.7428, implying that the predictions made by the SARIMA model would be within (plus or minus) 0.7428 of true TB incidence per 100,000 populations.

## Tools and Libraries

RStudio Software. (tidyverse, ggfortify, tseries and forecast packages)

## Contributions

Contributions to enhance the functionality and reliability of the models are welcome. Please fork the repository, make your changes, and submit a pull request. For significant changes, please open an issue first to discuss your proposed modifications.
