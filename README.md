# Stock-Market-Prediction-and-Forecasting

Toyota Stock Price Prediction

This project focuses on time series analysis and forecasting for Toyota Motors stock prices using a dataset spanning from 1980 to 2024. The project involves data exploration, statistical analysis, and the application of ARIMA models for stock price prediction.

Dataset
The dataset used for this analysis is provided in the file Toyota_Data.csv and contains the following columns:

Date: The date of the stock price entry.
Adj Close: Adjusted closing price of Toyota Motors stock.
Close: The closing price of the stock.
High: The highest price during the trading day.
Low: The lowest price during the trading day.
Open: The opening price at the start of the trading day.
Volume: The number of shares traded.
Project Workflow
Data Loading and Preprocessing:

Load the dataset and set the Date column as the index after converting it to a datetime format.
Exploratory Data Analysis (EDA):

Overview of the dataset (e.g., shape, missing values, and descriptive statistics).
Visualization of Toyota Motors' closing price over time from 1980 to 2024.
Correlation heatmap to understand relationships between different stock features (e.g., Close, High, Low, etc.).
Stationarity Test:

Use the Augmented Dickey-Fuller (ADF) test to check whether the stock prices' time series is stationary, which is crucial for forecasting models like ARIMA.
Time Series Differencing:

If the time series is not stationary, differencing is applied to stabilize it for model fitting.
Forecasting Model (ARIMA):

After ensuring stationarity, ARIMA models are applied to predict future stock prices based on historical data.

Visualizations
The notebook generates several key plots, including:

Stock Closing Price Trend: A plot showing the Toyota stock's closing price over time.
Correlation Heatmap: A heatmap showing the relationships between stock features.

Conclusion
This project demonstrates how time series data of stock prices can be analyzed for predictive modeling using ARIMA. The dataset was preprocessed, analyzed for trends, and transformed to ensure stationarity, enabling accurate forecasting of future stock prices.

