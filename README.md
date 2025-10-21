# StocksSentimentAnalysisProject

Stocks Sentiment Analyzer (FinBERT + Yahoo Finance + NewsAPI)

This project combines financial data and news sentiment analysis to explore how market sentiment correlates with stock price movements.
It uses the FinBERT model for finance-specific sentiment classification and visualizes the relationship between stock price, RSI, and sentiment polarity over time.

Features----------

Fetch live stock data from Yahoo Finance using yfinance

Calculate RSI (Relative Strength Index) using the ta library for momentum analysis.

Scrape financial news via the NewsAPI

Run sentiment analysis on news articles using FinBERT

Merge sentiment and stock data to visualize correlation.

Interactive chart showing normalized stock price vs sentiment trends.

Compute correlation coefficient between daily sentiment and price returns.

Tech Stack
Category	Libraries / Tools
Data Retrieval	yfinance, newsapi-python
Data Processing	pandas, numpy
Financial Indicators	ta (RSIIndicator)
Sentiment Model	transformers (FinBERT)
Visualization	matplotlib
Environment	Google Colab
