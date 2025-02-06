Project: Stock Price Prediction Using Machine Learning

Objective: The goal of this project is to analyze historical stock data and predict future stock prices using machine learning models. By leveraging past trends and technical indicators, this project helps in understanding stock behavior and forecasting future movements.

About the Data - 
Source: Data is fetched from Yahoo Finance using the yfinance library.
Stocks Analyzed: NVIDIA (NVDA), Apple (AAPL), Tesla (TSLA), Microsoft (MSFT), Google (GOOGL), Amazon (AMZN).
Time Period: 5 years of historical stock price data.

Features Used:
Closing price
Lag features (previous days’ closing prices)
Simple Moving Averages (SMA_7, SMA_30)
Relative Strength Index (RSI)

Approach Used - 
Data Collection: Fetched historical stock price data for selected companies.

Exploratory Data Analysis (EDA):
Visualized stock trends over time.
Computed summary statistics.
Analyzed correlation among stock prices.

Feature Engineering:
Created lag features for past closing prices.
Calculated moving averages and RSI for trend analysis.

Modeling:
Trained multiple machine learning models, including Random Forest Regressor.
Evaluated models using RMSE and R² scores.

Questions Explored:
1. How do stock prices of different companies correlate with each other?
2. What are the key indicators that impact stock price movements?
3. Can machine learning effectively predict future stock prices?
4. Which model performs best in predicting stock trends?

Limitations:
Stock prices are influenced by external factors like news, earnings reports, and market sentiment, which are not captured in this model.
The model assumes that historical patterns repeat, which may not always be the case.
Limited to six stocks and does not account for broader market indicators.

Results:
The Random Forest Regressor was trained and evaluated for each stock.
The model performed reasonably well but has limitations in accurately predicting future prices due to market volatility.
Important indicators for price prediction: Lag Features, SMA, RSI.

Future Improvements:
Incorporate sentiment analysis on news and social media data.
Test additional models like LSTMs for time-series forecasting.
Expand analysis to more stocks and broader market indices.
