# ORIE 4741 Individual Price Prediction for S&P500 Stock 
by Jiahui Lu (jl3947), Wenjia Zhai (wz363), Yishan Xiong (yx468)

(We have changed the project topic from "s&p500_stock_price_prediction_in_bear_market" to the current one.)

### Introduction
The stock trading is exciting for its uncertainty, however, for the future practitioner in financial industry, we believe that
there are certain rules lying in the numbers. Traditionally, people use linear multifactorial model to predict future stock price
to reduce the possible risks and maximize the profit.
In this project, we are going to use several machine learning models to predict the future stock price. We plan to utilize efficient models such as Ridge, Lasso, Huber, Random Tree, and XGBoost to achieve our goal. And then compare their prediction power.

### Our data set:
Daily price/volume/industry data of S&P500 stocks from Wharton database.

### Our steps: 

1. Feature engineering: Ordinal data: stock fundamental information data (like industry category), Numeric data: stock price data, stock’s volume data
2. Modeling: Ridge, Lasso, Huber, Random Tree, and XGBoost
3. Comparing: Using backtest results from the models above, compare the accuracy and complexity of algorithms 
4. Limitation and possible solutions

### Expected outcome:
Finding a machine learning model which could predict the individual stock price with relatively high accuracy.

