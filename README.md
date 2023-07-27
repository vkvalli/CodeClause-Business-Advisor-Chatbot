# Business Advisor Chatbot

This is a Flask-based Python chatbot that provides business advice by analyzing the historical stock data of 5 different companies: Apple, Google, Ford, Pfizer, and Tesla. The chatbot can provide historical stock data analysis, show graphical representations of the data, and give future stock price predictions.

## Dataset Description

The dataset used in this analysis contains the following columns:

* Date: Date of Listing (YYYY-MM-DD)
* Open: Price when the market opens
* High: Highest recorded price for the day
* Low: Lowest recorded price for the day
* Close: Price when the market closes
* Adj Close: Modified closing price based on corporate actions
* Volume: Amount of stocks sold in a day

You can find all the datasets at: https://www.kaggle.com/datasets

## Analysis Performed

* Daily Returns: Calculated the daily percentage change in stock prices to measure the investment's daily performance.
* Moving Averages: Computed moving averages to identify trends and smooth out short-term fluctuations in stock prices.
* Trading Signals: Generated trading signals by comparing short-term and long-term moving averages to determine buy or sell opportunities.
* Cumulative Returns: Calculated the cumulative returns over a given period to evaluate the overall investment performance.
* Relative Strength Analysis: We analyzed the relative strength of Airbnb's stock compared to a benchmark index to assess its strength against the market.
* Breakout Analysis: Identified potential breakout points in the stock's price movement to anticipate significant price movements.
* Market Sentiment Analysis: Conducted sentiment analysis using various techniques to gauge market sentiment toward Airbnb's stock.
