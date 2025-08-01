# Tesla Stock Market Prediction

## Task Objective

The goal of this project was to build a **short-term stock price prediction model for Tesla (TSLA)** using historical market data. The model predicts future stock prices based on common trading indicators to help identify short-term trends and movements.

---

## Dataset Used

- **Source**: Yahoo Finance via `yfinance` API  
- **Ticker**: TSLA (Tesla Inc.)  
- **Date Range**: January 2020 to August 2025  
- **Features Used**:
  - Open
  - High
  - Low
  - Close
  - Volume

---

## Models Applied

- **Linear Regression**
  - Used for predicting the closing stock price
  - Trained on normalized historical data using scikit-learn

---

## Key Results and Findings

- Achieved an **R² score of 0.98**, indicating strong predictive performance on short-term trends  
- Model captured the relationship between daily trading features and next-day closing prices effectively  
- Despite its simplicity, the linear regression model delivered accurate results, making it a good **baseline** for further experimentation  
- Potential to expand into more advanced time-series forecasting using LSTM or ensemble models

---
