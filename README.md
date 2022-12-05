# Realtime Orderbook Extraction from Kraken
Extract realtime orderbook data (price and volume) on Jupyter notebook for the following currency pairs BTC/USD, BTC/USDT, BTC/USDC, BTC/EUR, BTC/GBP, BTC/JPY. 

Steps to follow:
1) Place the krakenwsbook.py file in the same folder as the Jupyter notebook you are working on
2) Run the following one line in a shell in your notebook. This will extract the 10 highest bids and 10 lowest asks for BTC/USD pair:
**%run ./krakenwsbook.py BTC/USD 10**
3) The output will give you the most recent 10 highest Bid and 10 lowest Ask for BTC/USD pair with their volumes in parantheses
4) To stop execution, interrupt the kernel
5) Modify the one line of code in your choice of currency pair and number of orders you want to see on your screen 
6) For more details check out https://docs.kraken.com/websockets/
