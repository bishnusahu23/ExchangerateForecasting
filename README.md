# FORECASTING EXCHANGE RATES USING TIME SERIES ANALYSIS
## Objective:
Leverage ARIMA, SARIMA and Exponential Smoothing techniques to forecast future exchange rates USD to Australian Dollar based on historical data. 
## Dataset:
The dataset contains historical exchange rate with each column representing a different currency rate over time. The first column indicates the date, and second column represent exchange rates USD to Australian Dollar.
## Analysis:
In developing the exchange rate forecasting model, several methods were employed to ensure accurate and reliable predictions. The initial step involved exploratory data analysis (EDA) to visualize trends, seasonality, and stationarity within the dataset. This analysis was followed by the application of Exponential Smoothing techniques, which were chosen for their ability to effectively capture both trend and seasonal patterns in the data. Additionally, ARIMA and SARIMA models were considered to account for potential autoregressive and moving average components. The model selection process involved comparing various configurations of these methods, guided by performance metrics such as Akaike Information Criterion (AIC) and Bayesian Information Criterion (BIC) to evaluate model fit. Finally, cross-validation techniques were utilized to assess the robustness of the models and to minimize the risk of overfitting, ensuring that the selected model generalizes well to unseen data.
## Conclusion:
In conclusion, we ultimately selected Exponential Smoothing for our exchange rate forecasting model due to its ability to effectively capture both trends and seasonal patterns while remaining adaptable to changes in the data. Its simplicity and robustness made it a preferable choice over more complex models like ARIMA and SARIMA.
