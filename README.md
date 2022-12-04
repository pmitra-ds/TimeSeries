# TimeSeriesForecasting
In this exercise the time series forecasting is performed using  monthly Atmospheric CO2 from Continuous Air Samples at Mauna Loa Observatory, Hawaii, U.S.A., with the period of Record: March 1958 to December 2001. the dataset is available in statsmodel database. It has a a visible trend and seasonality. A 12 month forecasting (the year of 2001) is shown for two models - 
1. Simple Exponential Smoothing (SES) with Seasonal-Trend decomposition using LOESS (STL) 
2. Auto-Arima (has seasonal components)


The overall accuracy is better for STL+SES (MSE=0.21) than ARIMA(MSE=0.32), however, the seasonal peak is better modelled by arima.

