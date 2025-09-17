# Stock-price-Predictor-using-GRU-Gated-Recurrent-Unit-
A GRU (RNN) model that can predict stock prices for the next day and upcoming 7 days 
📈 Stock Price Prediction using GRU
## Overview:
This project demonstrates how to use Gated Recurrent Units (GRU) for time-series forecasting of stock prices.
We build two models:
-->>>>Single-step GRU → Predicts the next day’s stock price.
-->>>>Multi-step GRU → Predicts the next 7 days’ stock prices.

The project is implemented in Google Colab using Python, TensorFlow/Keras, and Yahoo Finance API.

## ⚡ Features:

Fetches real-time stock data using Yahoo Finance
Preprocesses and scales the data for GRU input.
Trains:
-->>>> Single-step model (1-day forecast)
-->>>> Multi-step model (7-day forecast)
## Evaluates using RMSE and MAE metrics.
## Visualizes actual vs predicted stock prices.

-->>>>Flexible to use with any ticker symbol (e.g., TSLA, AAPL, BTC-USD).

🛠️ Tech Stack

-->>>>Python 3
-->>>>TensorFlow / Keras
-->>>>yfinance

pandas, numpy, scikit-learn

matplotlib / plotly
