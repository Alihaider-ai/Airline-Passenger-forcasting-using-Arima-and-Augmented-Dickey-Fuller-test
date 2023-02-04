# International Airline Passenger Forecast with ARIMA
This project uses the ARIMA (AutoRegressive Integrated Moving Average) method to forecast the monthly totals of international airline passengers from 1949 to 1960. 

# Requirements
The following packages are required to run the code:

NumPy
Pandas
Matplotlib
Statsmodels

# Results
Before building the ARIMA model, the time series data was tested for stationarity using the Augmented Dickey-Fuller (ADF) test. The results showed that the data is stationary, with an ADF Statistic of -4.29 and a p-value of 0.000461.

The ARIMA model was then fitted to the data and was able to provide accurate forecasts for the monthly totals of international airline passengers . The results are visualized in the Jupyter Notebook file, and the code can be modified to change the parameters and explore different forecasting scenarios.

# Conclusion
This project demonstrates the potential of the ARIMA method for time series forecasting, and provides a framework for further analysis and experimentation with the dataset. By continuing to improve the model and explore other methods, it may be possible to further improve the accuracy of the forecasts.
