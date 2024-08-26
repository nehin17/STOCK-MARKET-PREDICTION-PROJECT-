# STOCK-MARKET-PREDICTION-PROJECT-
overview:
This project aims to predict future stock prices and turnover using historical stock market data. The primary focus is on building and evaluating multiple machine learning models to forecast stock prices and turnover, including Linear Regression, Random Forest Regressor, Support Vector Machine (SVM), and Polynomial Regression.

dataset used: NIFTY 50 stock market data.

Columns: Date, Open, High, Low, Close, Shares Traded, Turnover (₹ Cr), Prev Close, Prev High, Prev Low, 7-day MA, 30-day MA, Daily Return, Volatility, Rolling_Mean_7, Rolling_Std_7.

Moving Averages: 7-day and 30-day moving averages.

Volatility: Rolling volatility.

Polynomial Features: Polynomial features for relationships between stock prices, close, and open prices.

Machine Learning Models used-
  1. Linear Regression
  2. Random Forest Regressor
  3. Support Vector Machine (SVM)

Evaluation metrics: mean absolute error (MAE), mean squared error (MSE), R² Score.

Target Variables- 
   1. Turnover (₹ Cr): for predicting turnovers
   2. Close: for predicting future stock prices

Findings-
   1. Random Forest Regressor has the lowest MAE for predicting future turnovers
   2. Linear Regression has the lowest MAE for predicting future stock prices 
