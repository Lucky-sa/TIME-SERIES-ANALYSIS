This notebook is a time series analysis project on portfolio stock and crypto data, mainly focusing on visualization and decomposition of trends/seasonality.

Main activities inside the notebook:
Imports libraries like pandas, matplotlib, and statsmodels.tsa.seasonal.
Loads financial data from a CSV file (portfolio_data.csv) containing stock and crypto prices.

Prepares the dataset:
Converts a Date column into datetime format.
Sets Date as the index for time series analysis.

Plots stock/crypto closing prices for:
Amazon (AMZN)
Domino’s Pizza (DPZ)
Bitcoin (BTC)
Netflix (NFLX)
Performs seasonal decomposition (multiplicative model, period = 12) on Amazon stock prices to analyze trend and seasonality.
