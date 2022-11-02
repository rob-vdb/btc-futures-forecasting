# Bitcoin Futures Price Forecasting (in progress)

I am using Python to forecast the price of Bitcoin futures contracts traded on FTX (an online cryptocurrency and cryptocurrency derivatives exchange). I am using the scikit-learn library as well as the Support Vector Regression Machine Learning algorithm to forecast these prices. The dataset is comprised of price and trading volume data (collected at 15-minute intervals) for Bitcoin as well as Bitcoin futures contracts traded on FTX from September 2019 through to May 2022. The time series for different Bitcoin futures were concatenated, and overlaps were avoided by focussing on the futures contract in the current quarter. This is referred to as the "CQF (Current Quarter Futures) Close" price in the notebok. 

NOTE: the data were retrieved using a private API key, and so the notebook used to acquire the data has not been uploaded. 
