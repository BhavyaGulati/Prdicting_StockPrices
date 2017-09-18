# Prdicting_StockPrices
Predicting closing prices of stock using Tensorflow and sentiment analysis using tweety and textblob

The python script "Predict_Stock.py" does the following:
1.Asks the user for a stock quote from NASDAQ (eg: AAPL, FB, GOOGL)
2.Uses Tweepy to retrieve tweets about that stock.

3.Uses TextBlob to determine if the majority of the tweets are positive using sentiment analisys.

4.If the last is True, downloads the last year of prices for that stock, and trains a neural net with that data to predict the

price for tomorrow.

