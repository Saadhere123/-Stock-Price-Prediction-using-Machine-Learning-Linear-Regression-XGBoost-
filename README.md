                              📈 Stock Price Prediction using Machine Learning (Linear Regression + XGBoost)

This project predicts the **next day closing price of a stock** using machine learning models. It compares **Linear Regression** and **XGBoost Regressor** on historical stock data.

---

🚀 Project Overview

- Fetch stock data using `yfinance`
- Perform feature engineering (lags, moving averages, volatility)
- Train ML models
- Predict next-day stock closing price
- Compare model performance

---

📊 Models Used

1. Linear Regression
Simple baseline regression model.

2. XGBoost Regressor
Advanced gradient boosting model for structured data.

---

📁 Dataset

- Source: Yahoo Finance (`yfinance`)
- Stock: **AAPL (Apple Inc.)**
- Time Range: **2020 - 2025**

Features:
- Open, High, Low, Volume
- Lag features (Prev Close, Close_lag2, Close_lag3)
- Moving Averages (MA5, MA10, MA20)
- Volatility (STD5)

Target:
- Next day closing price

---

⚙️ Installation

```bash
pip install yfinance pandas numpy matplotlib scikit-learn xgboost
