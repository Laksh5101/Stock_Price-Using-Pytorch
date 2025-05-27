# Stock Price Prediction Using LSTM (PyTorch)

## Project Overview

This project demonstrates how to forecast stock prices using Long Short-Term Memory (LSTM) neural networks implemented with PyTorch. The model is trained on historical stock price data to predict future values based on past patterns.

The example uses Apple Inc. (AAPL) stock data from 2010 to 2024, and predicts the next 30 days of stock prices.

---

## Features

- Download historical stock price data via Yahoo Finance using yfinance.
- Preprocess and scale stock data with MinMaxScaler.
- Create time series sequences for LSTM input.
- Build a 2-layer LSTM model with dropout regularization using PyTorch.
- Train the model using MSE loss and Adam optimizer.
- Iteratively predict stock prices for the next 30 days.
- Visualize actual vs predicted prices using matplotlib.

---

## Technologies & Libraries

- Python 3.x
- [yfinance](https://pypi.org/project/yfinance/) — for fetching stock data
- [numpy](https://numpy.org/) — numerical operations
- [pandas](https://pandas.pydata.org/) — data manipulation
- [scikit-learn](https://scikit-learn.org/stable/) — data scaling
- [Pytorch](https://pytorch.org/) — deep learning
- [Matplotlib](https://matplotlib.org/) — data visualization

---

## Installation

1. Clone this repository or download the project files.
Install required packages:
pip install yfinance numpy pandas scikit-learn pytorch matplotlib
Usage
Open the Jupyter Notebook or Python script containing the project code.

Run the cells or script sequentially:

Download and preprocess stock data

Create sequences for training

Build and compile the LSTM model

Train the model

Predict and visualize future stock prices

Modify the ticker variable in the code to predict other stock symbols.

## Usage
Open the stock_price_prediction.ipynb notebook and run the cells step by step:

1. Download and preprocess historical stock price data

2. Generate time sequences for LSTM input

3. Build and train the LSTM model

4. Predict the next 30 days based on last 60 days

5. Visualize actual vs predicted prices

✅ You can modify the ticker variable (default: 'AAPL') to predict prices for other stocks.

## Project Structure
.
- ├── stock_price_prediction.ipynb   # Jupyter notebook with full code and explanations
- ├── README.md                      # This README file


