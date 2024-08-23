# Stock Volatility Modeling using GARCH

This project aims to model the volatility of two selected stocks using the Generalized Autoregressive Conditional Heteroskedasticity (GARCH) model. The workflow includes identifying the appropriate lags using the Partial Autocorrelation Function (PACF), implementing a rolling forecast to validate the model, and predicting the next 7 days of volatility.

## Project Overview

1. **Data Collection**: 
   - Retrieve historical price data for two selected stocks.
   - Calculate daily returns from the price data.

2. **PACF Analysis**:
   - Compute the Partial Autocorrelation Function (PACF) for the returns to identify the significant lags that influence volatility.
   
3. **GARCH Model Implementation**:
   - Use the identified lags from PACF to configure the GARCH model.
   - Fit the GARCH model to the returns data for each stock.

4. **Rolling Forecast**:
   - Implement a rolling forecast to predict volatility over a specified window.
   - Compare the predicted volatility with the actual observed volatility to assess model accuracy.

5. **7-Day Volatility Prediction**:
   - Use the trained GARCH model to predict the next 7 days of volatility for each stock.
   - Visualize the predicted volatility against historical data.
