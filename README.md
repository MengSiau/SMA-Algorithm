# SMA-Algorithm
A simple trading algorithm using Simple Moving Average as a technical indicator.

# Purpose of project
This project was created during my first year of university and was intended to improve my familarity with Python and it's common data science libraries. Looking to add more indicators later in the future. 

# How it works 
Using data from MetaTrader5 API, this algorithm begins with $10,000 and trades with EURUSD (can be changed) on a daily interval. The SMA indicator works by taking two moving averages; The slow moving average and the fast moving average. The slow moving average takes in the closing price of EURUSD within the last 100 days and calculates the moving average. Similarly, the fast moving average takes in opening prices of EURUSD within the last 10 days. If the fast moving average crosses above the slow moving average, we generate a "Bullish crossover" signal. Conversely, if the fast moving average crosses below the slow moving average, we generate a "Bearish crossover." We will buy a volume of 100,000 if it is a bullish crossover and sell if it is a bearish crossover. 



