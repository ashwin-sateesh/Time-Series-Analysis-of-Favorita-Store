# Time-Series-Analysis-of-Favorita-Store

This project aims to build a forecasting model that accurately predicts the unit sales of items sold at various Favorita stores, a grocery retailer based in Ecuador. The goal is to observe and deduce trends in sales based on various factors such as stores, promotions, holidays, etc., and understand how external factors affect sales.

EDA was done to understand how various factors such as seasons and holidays affect sales and to understand the trends in sales of a particular family of products across the years. A stationarity check was performed after which the data was made stationary as time-series models work best with stationary data.

Various modelling techniques such as Regression models (XGBoost, Random Forest) and statistical models (Holt winters exponential smoothing, ARIMA and SARIMAX) were used to predict future sales. After running and predicting using the various models, it was concluded that different models at different levels of prediction were suaitable for various use cases.

## Dataset

The dataset consists of 4 years of sales data at a date-store-product level, along with information on promotions, store details, holidays/events, and daily oil prices. 

### Key Data Sources

1. **Sales Data**: Daily sales data with information on store, product family, and promotions.
2. **Store Data**: Details about the 54 Favorita stores including location, type, and cluster.
3. **Holidays Data**: Information on national, regional, and local holidays in Ecuador.
4. **Transactions Data**: Number of transactions per store per day.

## Modeling Techniques

### Statistical Forecasting Models
1. **Holt-Winters Exponential Smoothing**: Used for yearly per-unit sales forecasting for the next n months, useful for annual budgets and company review.
2. **ARIMA (Auto Regressive Integrated Moving Average)**: Used for monthly per-unit sales forecasting for the next n months, helpful for supply chain and demand forecasting planning.
3. **SARIMAX (Seasonal ARIMA with Exogenous Variables)**: Used for monthly per-unit sales forecasting for the next n months, considering external factors like holidays. Useful for supply chain and demand forecasting planning.

### Machine Learning Models
1. **Random Forest and Xgboost**: Used for daily per-unit sales forecasting per store for the next year, helpful for resource allocation and cash flow management planning.

## Evaluation Metric

- **Mean Absolute Percentage Error (MAPE)**: Used to measure the accuracy of forecast models.

## Results

Different models were applied to various use cases to optimize forecasts across multiple functions such as supply chain, budget planning, and inventory management.

## Appendix
Additional visualizations and code snippets are provided in the report. For more detailed information, please refer to the project report.
