# 📈 Stock Price Prediction using RNN, LSTM, and GRU

This project demonstrates how to use **Recurrent Neural Networks (RNNs)**, **Long Short-Term Memory (LSTM)**, and **Gated Recurrent Units (GRU)** for **time-series forecasting** on real-world stock data.

The goal is to predict the **next day's closing price** of a stock based on its past 60 days of prices and compare the performance of different recurrent architectures.

---

## 🚀 Features

- Fetches **10 years of historical stock data** automatically using `yfinance`.
- Compares **Simple RNN**, **LSTM**, and **GRU** models on the same dataset.
- Evaluates models using key regression metrics:
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
  - Mean Absolute Error (MAE)
  - R² Score
- Visualizes:
  - Training & validation loss across epochs.
  - Actual vs Predicted stock prices.
- Easy to customize for any stock symbol.

---

## 🧠 Models Compared

| Model | Key Feature | Strength |
|--------|--------------|-----------|
| Simple RNN | Basic recurrent architecture | Fast but struggles with long-term dependencies |
| LSTM | Uses cell state & gates | Handles long-term patterns better |
| GRU | Simplified LSTM with fewer parameters | Efficient and often performs equally well |

---

## 🛠️ Tech Stack

- **Python 3.10+**
- **TensorFlow / Keras**
- **NumPy**, **Pandas**
- **Matplotlib**
- **Scikit-learn**
- **yfinance**

---

## 📦 Installation

Clone the repository and install required libraries:

```bash
git clone https://github.com/yourusername/stock-prediction-rnn-lstm-gru.git
cd stock-prediction-rnn-lstm-gru
pip install -r requirements.txt
