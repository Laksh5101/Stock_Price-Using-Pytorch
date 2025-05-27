# Stock Price Prediction Using LSTM

## Project Overview

This project aims to predict future stock prices using historical stock data and deep learning techniques. Specifically, an LSTM (Long Short-Term Memory) neural network model is trained on past stock price sequences to forecast future prices.

The example in this project uses Apple's (AAPL) historical stock prices from 2010 to 2024 and predicts the next 30 days of stock prices.

---

## Features

- Download historical stock price data using the Yahoo Finance API (`yfinance`).
- Preprocess data and normalize stock prices for model training.
- Create sequential time series data suitable for LSTM input.
- Build and train an LSTM model to capture temporal dependencies in stock prices.
- Predict future stock prices iteratively.
- Visualize historical and predicted stock prices using Matplotlib.

---

## Technologies & Libraries

- Python 3.x
- [yfinance](https://pypi.org/project/yfinance/) — for fetching stock data
- [numpy](https://numpy.org/) — numerical operations
- [pandas](https://pandas.pydata.org/) — data manipulation
- [scikit-learn](https://scikit-learn.org/stable/) — data scaling
- [TensorFlow / Keras](https://www.tensorflow.org/) — deep learning
- [Matplotlib](https://matplotlib.org/) — data visualization

---

## Installation

1. Clone this repository or download the project files.
Install required packages:
pip install yfinance numpy pandas scikit-learn tensorflow matplotlib
Usage
Open the Jupyter Notebook or Python script containing the project code.

Run the cells or script sequentially:

Download and preprocess stock data

Create sequences for training

Build and compile the LSTM model

Train the model

Predict and visualize future stock prices

Modify the ticker variable in the code to predict other stock symbols.

## Project Structure
.
- ├── stock_price_prediction.ipynb   # Jupyter notebook with full code and explanations
- ├── README.md                      # This README file

