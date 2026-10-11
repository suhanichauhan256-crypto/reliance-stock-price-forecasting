# Reliance Stock Price Forecasting Using Time Series Analysis

## Project Overview
This project analyzes five years of historical Reliance Industries stock price data using Python and time series analysis. An ARIMA model is used to forecast stock prices.

## Tools and Technologies
- Python
- Pandas and NumPy
- Matplotlib
- yfinance
- Statsmodels
- Scikit-learn

## Project Workflow
1. Collected historical stock data using yfinance.
2. Cleaned and checked the dataset.
3. Performed exploratory data analysis (EDA).
4. Split the data into training and testing sets.
5. Built an ARIMA(1,1,1) model.
6. Evaluated the model using MAE and RMSE.
7. Compared the results with a naive baseline.

## Results
- ARIMA MAE: ₹80.65
- ARIMA RMSE: ₹98.97
- Fixed-horizon baseline MAE: ₹80.65
- Fixed-horizon baseline RMSE: ₹99.00

The ARIMA(1,1,1) model achieved an MAE of ₹80.65 and an RMSE of ₹98.97. The fixed-horizon baseline achieved an MAE of ₹80.65 and an RMSE of ₹99.00. Both approaches produced very similar results, with ARIMA showing a negligible improvement in RMSE. This comparison uses the same test period for both methods. The forecasting approaches used different evaluation methods, so the results should be compared carefully.

## Conclusion
This project demonstrates data collection, data cleaning, exploratory data analysis, time series forecasting, visualization, and model evaluation. Future work could include tuning ARIMA parameters and comparing models using a consistent evaluation method.

## Disclaimer
This project is for educational purposes only and is not investment advice. Stock prices are unpredictable, and forecasts should not be used alone to make investment decisions.
