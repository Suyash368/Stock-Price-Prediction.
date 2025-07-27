# 📈 Stock Market Prediction using LSTM in Python

This project demonstrates how to use Long Short-Term Memory (LSTM), a type of Recurrent Neural Network (RNN), to predict stock prices using historical data. It is inspired by the DataCamp tutorial on building LSTM models for stock market forecasting.

## What is LSTM?

LSTM networks are a special kind of RNN, capable of learning long-term dependencies. They are particularly well-suited for time-series prediction tasks like stock market forecasting due to their ability to remember past information.

## Project Overview

In this project, we:

- Collected historical stock price data using the Yahoo Finance API via the `yfinance` package.
- Preprocessed and normalized the data using MinMaxScaler.
- Built a multi-layered LSTM model using Keras and TensorFlow.
- Trained the model and evaluated its performance on unseen data.
- Visualized predicted vs actual stock prices.

## Technologies Used

- Python 
- Pandas & NumPy
- Matplotlib & Plotly
- scikit-learn
- TensorFlow / Keras
- yfinance

## Project Structure
-📄 README.md                # Project documentation
-📄 requirements.txt         # List of required Python libraries
-📄 stock_lstm_model.py      # Main Python script (LSTM model & prediction logic)
-📓 stock_prediction.ipynb   # Jupyter notebook version (step-by-step walkthrough)
-📁 data/                     # Folder to store downloaded stock data (CSV files)│ 
-📁 images/                  # Visualizations and result plots


