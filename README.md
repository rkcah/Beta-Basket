# Beta Basket

It is a strategy for Indian equity markets which provides exposure to high momentum stocks with volatility based sizing.

The strategy is as follows:

1. Create an universe of stocks

2. Create two filters the NIFTY 200 day SMA and the stocks 100 day moving SMA.They act as macroeconomic filters and stops trading incase the respective price is below the average.

3. Beta and R-Squared Values are calculated from a Running Regression of the log of closing prices and the date indexes. 

4. Stocks are ranked using the beta* R-squared values 
 
5. Rebalancing is done every Wednesday, and if the market is closed on the next possible day.

6. Position Sizing is done using Average True Range

Results are present in the Jupyter Notebook
