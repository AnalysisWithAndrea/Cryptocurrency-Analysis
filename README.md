# Cryptocurrency-Analysis

## Data Collection
Downloaded the Ethereum, Bitcoin, Cardano, and Dogecoin datasets from [Yahoo Finance]( https://finance.yahoo.com/cryptocurrencies/?guccounter=1&guce_referrer=aHR0cHM6Ly93d3cuZ29vZ2xlLmNvbS8&guce_referrer_sig=AQAAADRBJKG_tdcNwG2RPsqHsSf4m557DrcowNHzCFWNSf_hN__9A3mlZvWdC71hfRSjpX4aLZLkQvWc3lcBEEigtTylwESvvFLq5WYby7wbtbk2uhPKqwo_cplRAWpjPjd1qKrwLJSgNNGmTmMXCyskZvLi_MAshqBc4r17Y7cvpGDA). 
## Data Exploration
I used Python to check some stats of the data such as number of rows, max/min values, mean values, checked for null values, checked data types, normalized closing values. I also set date as the index of the dataframe. Then, I calculated the moving averages over a 10, 20, and 50 day time period, derived the daily return using the percentage change over the adjusted closing price, created a correlation matrix, and quantified the risk of investment using the expected return and the std. deviation of the daily returns. Lastly, I calculated the value at risk using the quantile function.
## Visualizations
Created comprehensive graphs using matplotlib and seaborn libraries. I plotted the closing value, volume traded, moving averages, and daily return over time, normalized closing value over time, correlation of daily returns as well as closing values, and the risk vs. the expected return. 
## Findings 
* Bitcoin = low risk low return
* Ethereum = low risk medium return
* Cardano = medium risk medium return
* Doge = high risk high return







