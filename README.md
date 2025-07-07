**Gold Price Forecasting using Time Series Analysis in R**

This project focuses on forecasting future gold prices using time series analysis in RStudio. Leveraging 24 years of historical gold price data, the analysis aims to understand long-term patterns and generate a 10-month forecast using statistical modeling techniques.

📌 Objective
To analyse and forecast gold price trends using time series models such as ARIMA, SARIMA, and ARMA-GARCH, and evaluate their performance for short-term prediction. The goal is to identify seasonality and volatility patterns in gold prices and select the best model for accurate forecasting.

🔍 Key Highlights
- Dataset: Daily gold price data from 2000 to 2023

- Performed data cleaning and transformation to prepare for modeling

- Conducted exploratory time series analysis to identify trend and seasonality

*Evaluated three core models:*

= ARIMA for general forecasting

- SARIMA to account for seasonality

- ARMA-GARCH to model both time dependence and volatility

**Based on the observed seasonal patterns, SARIMA outperformed others in terms of fit and forecast accuracy**

Generated a 10-month gold price forecast, revealing a positive trend in the near future

📈 Results
SARIMA was identified as the most suitable model due to recurring seasonal trends in the gold price data

The model captured both trend and seasonality effectively, offering a reliable forecast with confidence intervals

Forecast visualisations clearly show an upward movement in gold prices over the next 10 months

🧠 Time Series Models Used
ARIMA (AutoRegressive Integrated Moving Average)

SARIMA (Seasonal ARIMA)

ARMA-GARCH (AutoRegressive Moving Average + Generalized Autoregressive Conditional Heteroskedasticity)

Model selection was based on AIC/BIC scores and residual diagnostics.

🧰 Tools & Libraries
RStudio

Forecast package for ARIMA/SARIMA modeling

Tseries for stationarity testing and diagnostics

Rugarch for GARCH modeling

GGPlot2 and Base R plotting for time series visualisation
