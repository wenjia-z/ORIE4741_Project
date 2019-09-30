# ORIE 4741 S&P500 Stock Price Prediction in Bear Market
by Jiahui Lu (jl3947), Wenjia Zhai (wz363), Yishan Xiong (yx468)

### Introduction
The stock trading is exciting for its uncertainty, however, for the future practitioner in financial industry, we believe that there are certain rules lying in the numbers. Now we are experiencing the longest bull market in the history, but the worries of the market grow from institutes to individuals. The year of 2020 is predicted to be a difficult year for the stock market of America, since the economic cycle is reported to be in its early recession stage next years. Thus, it would be helpful to predict the stock price rise and fall pattern in the bear market to reduce the possible risks and maximize the profit.

### Our data set:
“New York Stock Exchange - S&P 500 companies historical prices with fundamental data” from Kaggle: https://www.kaggle.com/dgawlik/nyse

This dataset contains basic price and performance data. It has four parts:  

- prices.csv: Raw daily prices of individual S&P 500 component stocks. Most of the data spans from 2010 to the end of 2016. For companies new to the stock market, the date ranges are shorter.  
- prices-split-adjusted.csv: Daily stock prices after adjustments for splits.  
- fundamentals.csv: Metrics extracted from annual SEC 10K filings (2012-2016). It could be used to derive fundamental features like PE ratio.  
- securities.csv: General description of each company. 

### Our steps: 

1. Feature engineering: Ordinal data: stock fundamental information data, Numeric data: stock price data, stock’s company financial data
2. Modeling: decision tree, random forest, support vector machine algorithm and XGboost
3. Comparing: Using backtest results from the models above, compare the accuracy and complexity of algorithms 
4. Limitation and possible solutions

### Expected outcome:
Finding a machine learning model which could predict the rise and fall of stock price  with relatively high accuracy.

