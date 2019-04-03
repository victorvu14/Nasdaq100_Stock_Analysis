# Nasdaq100_Stock_Analysis

# Scope 

- Analyze relationship between the average daily return and the volatility (sd), for each symbol.

- Is (daily) profitability related with (daily) volatility? 

- Create a clustering of companies, using the mean and sd of daily returns as the spliting variables. 

# Task Performed 

1 . Import Data From Yahoo Finance using getSymbols function. Within the For loop, we use the daily return function to calculate the return per day of the stock.

2. Calculate correlation between daily return and volatility 

3. Use Elbow Method to determine the optimal numnber of clusters. The Elbow method looks at the total WSS as a function of the number of clusters. The total WSS or within sum squared measures the compactness of each cluster and we want it to be as small as possible. In other words, we try to lower the intra-cluster variation.

4. To understand the performance of each stock, we calculate the the sharpe ratio. Sharpe ratio is the avarage return earned per unit of volatility. 
