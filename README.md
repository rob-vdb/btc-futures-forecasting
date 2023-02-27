# Bitcoin Futures Price Forecasting (January 2023)

January 2023. This formed part of my BSc. Thesis Internship. I utilised Python to forecast the price of Bitcoin futures contracts using the scikit-learn library as well as the Support Vector Regression Machine Learning algorithm. The dataset is comprised of price and trading volume data (collected at 15-minute intervals) for Bitcoin as well as Bitcoin futures contracts traded on FTX from September 2019 through to May 2022. The time series for different Bitcoin futures were concatenated, and overlaps were avoided by focussing on the futures contract in the current quarter. This is referred to as the "CQF (Current Quarter Futures) Close" price in the notebok. 

NOTE: the data were retrieved using a private API key, and so the notebook used to acquire the data has not been uploaded. 
