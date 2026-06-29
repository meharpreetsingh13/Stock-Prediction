# Stock Price Prediction using Machine Learning

This project is a **collaborative machine learning project** focused on predicting 
stock price trends using historical market data. The aim is to analyze past stock 
prices and apply machine learning techniques to understand and predict future movements.

---

## Team Collaboration

This project was developed **together as a team** and all contributors actively 
participated in data analysis, model development, and result interpretation.

---

## Project Overview

Stock market prediction is challenging due to uncertainty and market volatility. 
In this project, we:

* Fetched real-time historical stock data using `yfinance`
* Analyzed and visualized closing price trends
* Performed data preprocessing and scaling using MinMaxScaler
* Built a **Linear Regression** model for stock price prediction
* Evaluated model performance using RMSE
* Forecasted the **next 30 days** of stock prices

---

## Technologies Used

| Tool | Purpose |
|------|---------|
| Python | Core language |
| yfinance | Fetch live historical stock data |
| Pandas & NumPy | Data processing |
| Matplotlib | Data visualization |
| Scikit-learn | Linear Regression, MinMaxScaler, RMSE |
| Google Colab / Jupyter Notebook | Development environment |

---

## Methodology

1. **Data Collection** — Downloaded historical AAPL stock data (2015–2024) via yfinance
2. **Exploratory Data Analysis (EDA)** — Visualized closing price trends, checked for nulls
3. **Preprocessing** — Scaled data using MinMaxScaler (0–1 range)
4. **Dataset Creation** — Used a sliding window (timespan) approach to create features
5. **Train/Test Split** — 70% training, 30% testing
6. **Model Training** — Linear Regression on windowed closing price sequences
7. **Evaluation** — Calculated Train RMSE and Test RMSE
8. **Forecasting** — Predicted next 30 days using recursive prediction

---

## Results

* Plotted actual vs predicted prices for both train and test sets
* Achieved low RMSE on test data showing strong trend following
* Generated a 30-day future price forecast with visualization
* All outputs and plots are available inside the notebook

---

## My Contributions 

* Set up data pipeline using `yfinance` for live stock data fetching
* Handled multi-level column issues from yfinance and fixed preprocessing bugs
* Built and trained the Linear Regression model with sliding window approach
* Implemented MinMaxScaler for normalization and inverse transformation
* Created train/test visualizations and 30-day forecast plots
* Debugged array shape errors in prediction pipeline
* Updated and maintained project documentation

---

## Future Enhancements

* Implement deep learning models (LSTM, GRU) for better accuracy
* Add technical indicators (RSI, MACD, Bollinger Bands)
* Support multiple stock tickers simultaneously
* Hyperparameter tuning for improved predictions
* Deploy as an interactive web application using Streamlit

---

## 📌 Note

This repository represents a **joint academic project** created through 
collaboration and shared learning. Individual contributions reflect personal 
understanding and implementation effort.
