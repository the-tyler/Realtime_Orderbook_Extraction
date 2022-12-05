# Realtime Orderbook Extraction from Kraken
Extract realtime orderbook data (price and volume) on Jupyter notebook for the following currency pairs BTC/USD, BTC/USDT, BTC/USDC, BTC/EUR, BTC/GBP, BTC/JPY. 

Steps to follow:
1) Place the **krakenwsbook.py** file in the same folder as the Jupyter notebook you are working on
2) Run the following one line in a shell in your notebook: **%run ./krakenwsbook.py BTC/USD 10**
4) The output will give you the most recent 10 highest Bids and 10 lowest Asks for BTC/USD pair with their sizes in parentheses
5) To stop execution, interrupt the kernel
6) Modify the one line of code in your choice of pair and number of orders you want to see on your screen 
7) For more details check out https://docs.kraken.com/websockets/
