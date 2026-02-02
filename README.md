📈 Stock Price Predictor using Machine Learning

A machine learning project that predicts stock closing prices using historical market data and technical indicators. The project leverages Linear Regression and Random Forest Regressor, using real-time data fetched from Yahoo Finance, and is implemented in Google Colab.

🚀 Features

Real-time stock data using Yahoo Finance

Technical indicators:

Simple Moving Average (SMA)

Exponential Moving Average (EMA)

Relative Strength Index (RSI)

Moving Average Convergence Divergence (MACD)

Machine learning models:

Linear Regression

Random Forest Regressor

Model comparison using MSE and R² score

Clear visualization of actual vs predicted prices

🛠️ Tech Stack

Python

Google Colab

pandas

numpy

matplotlib

scikit-learn

yfinance

📂 Repository Structure
Stock-Price-Predictor/
│
├── README.md
└── Stock_Price_Prediction.ipynb

📊 Dataset

Source: Yahoo Finance

Example Stock: AAPL (Apple Inc.)

Date Range: 2020-01-01 to 2025-01-01

Features

Open

High

Low

Volume

SMA (20, 50)

EMA (12, 26)

RSI

MACD Line

Signal Line

Target

Close Price

⚙️ How It Works

Fetch historical stock data using yfinance

Perform data preprocessing

Compute technical indicators

Train machine learning models

Evaluate models using MSE and R²

Visualize predictions

Predict next-day closing price

📈 Model Performance
Linear Regression (with Technical Indicators)

MSE: ~0.668

R² Score: ~0.9995

Random Forest Regressor

MSE: ~1.606

R² Score: ~0.9989

➡️ Linear Regression performed better due to strong linear relationships in the dataset.

📊 Visualization

The project includes plots comparing:

Actual stock prices

Linear Regression predictions

Random Forest predictions

These plots help visually assess model accuracy and trend alignment.

🧠 Key Insights

Feature engineering significantly improves prediction accuracy

Technical indicators enhance model performance

Simpler models can outperform complex ones with the right features

Random Forest did not outperform Linear Regression in this dataset

▶️ How to Run

Open Google Colab

Upload Stock_Price_Prediction.ipynb

Run cells sequentially

Modify stock ticker (e.g., RELIANCE.NS, TSLA) if needed

🔮 Future Improvements

LSTM / Deep Learning models

Buy/Sell signal generation

Multi-day price prediction

Streamlit web app

Hyperparameter tuning

🎓 Use Case

Academic mini / final-year project

Machine Learning portfolio project

Internship / placement showcase

Interview discussions

📌 License

This project is for educational and learning purposes.# Stock-Price-Predictor-using-Machine-Learning
To predict future stock prices using historical stock market data by applying Linear Regression.
