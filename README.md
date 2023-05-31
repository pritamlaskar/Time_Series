# Time_Series
Time series forecasting is the use of a model to predict future values based on previously observed values. A time series is a series of data points indexed or listed or graphed in time order. Forecasting involves taking models fit on historical data and using them to predict future observations. The purpose of time series analysis is generally two fold to understand or model the stochastic mechanisms that gives rise to an observed series and to predict or forecast the future values of a series
based on the history of that series. </br> </br>
**Assumptions in Time Series**</br>
• Time series data should be equally spaced over time.</br>
• Patterns of past data will propagate into future.</br>
• Cannot be used to predict random events(i.e. next tsunami etc.)</br></br>
**Components of Time Series**</br>
• ***Trend***: Observation of data over a long period of time.</br>
• ***Seasonality***: Repeated pattern observed between regular interval due to seasonal factor but within or less than 1 year.</br>
• ***Cyclic***: Up and down movement in a given trend where duration of cycle depends on type of business and industry. Cycles include: a) peak, b) recession, c) trough / depression, d) expansion.</br>
• ***Irregular***: Fluctuations in time series data when trend, cyclic, and seasonal variations are removed. It is unpredictable and non-random.</br>
</br>
My repository contains projects that involve forecasting of time-series. Some are: </br> </br>
***TimeSeries_TractorSales***: We predict sales of John Deere tractors using ARIMA and SARIMA. Libraries used include basic EDA libraries like pandas, numpy, seaborn, and matplotlib and stats libraries like statsmodels.api, statsmodels.graphics.tsa and statsmodels.metrics.
