# Orderbook
Contains programs for ordering inputted buy/sell orders - to be ran as a system process every N seconds (default 1 day), where as N decreases the refresh rate of prices are higher. Uses pro-rata feeding into FIFO for matching orders. 

# Frontend
Contains (most) of the frontend for the stock exchange system, written to share a SQL database with the orderbook (cross R/W). Allows for reading portfolios, balances, adding/deleting stock tickers, adding buy/sell orders at market. 
