# ORIE 4741 S&P500 Stock Price Prediction
by Jiahui Lu (jl3947), Wenjia Zhai (wz363), Yishan Xiong (yx468)

### Our data set:
“New York Stock Exchange - S&P 500 companies historical prices with fundamental data” from Kaggle: https://www.kaggle.com/dgawlik/nyse

This dataset contains four parts:  

- prices.csv: Raw daily prices of individual stocks. Most of the data spans from 2010 to the end of 2016. For companies new to the stock market, the date ranges are shorter.  
- prices-split-adjusted.csv: Daily stock prices after adjustments for splits.  
- fundamentals.csv: Metrics extracted from annual SEC 10K filings (2012-2016). It could be used to derive fundamental indicators.  
- securities.csv: General description of each company with division on sectors  

### Two focuses: 

- How to use SVM, decision tree, random forest and XGboost to predict S&P 500 Price.  
- Compare the results of the methods.

### Our steps: 

1. Feature engineering: Ordinal data: stock fundamental information data, Numeric data: stock price data, stock’s company financial data
2. Modeling: decision tree, random forest, support vector machine algorithm and XGboost
3. Comparing: Using backtest results from the models above, compare the accuracy and complexity of algorithms 
4. Limitation and possible solutions

### Expected outcome:
Finding a machine learning model which could predict the rise and fall of stock price  with relatively high accuracy.

