# Time-Series-Analysis-of-Favorita-Store

The goal of the project is to build a forecasting model that accurately predicts the unit sales of items sold at various Favorita stores. Additionally, we aim to observe and deduce trends in sales based on various factors such as stores, promotions, holidays etc. and understand how external factors affect sales.

The dataset consists of 4 years of sales data, at a date-store-product level, along with information on promotions run on particular days. Additionally, information about each store, holidays/events and the daily oil price for the given date range have been provided.
The various datasets were cleaned and merged to create the final dataset on which analysis was performed. 

EDA was done to understand how various factors such as seasons and holidays affect sales and to understand the trends in sales of a particular family of products across the years. A stationarity check was performed after which the data was made stationary as time-series models work best with stationary data.

Various modelling techniques such as Regression models (XGBoost, Random Forest) and statistical models (Holt winters exponential smoothing, ARIMA and SARIMAX) were used to predict future sales. After running and predicting using the various models, it was concluded that different models at different levels of prediction were suaitable for various use cases.
