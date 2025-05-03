# Analyzing-Risk-Sentiment-and-Predicting-Stock-Price-Trends-from-10-K-Filings-Using-LSTM
Abstract—We present a study that explores the relationship
between risk factor sentiment in 10-K filings and stock price
changes of S&P 500 companies. Using FinBERT, we extract
sentiment scores from the ”Item 1A. Risk Factors” sections across
multiple years (2007–2023). These scores are then compared
with yearly average stock price changes to reveal modest but
noticeable correlations. We train an LSTM model to predict
future stock movements based on sequences of sentiment scores
and extend the prediction using a rolling forecast up to April
2025. Finally, we build an interactive Streamlit web application
that allows users to explore sentiment and stock trends by
company, sector, or industry. Our system demonstrates how
financial text analysis can support intuitive forecasting and
interactive data-driven decision-making.

Index Terms—Financial sentiment analysis, 10-K filings, risk
factors, stock price prediction, FinBERT, LSTM, time series
forecasting, Streamlit web app, S&P 500, rolling forecast
