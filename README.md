📈 Stock Price Prediction using Machine Learning

This project predicts stock prices using LSTM (Long Short-Term Memory), a type of Recurrent Neural Network well-suited for time-series forecasting. The model is trained on stock closing prices fetched directly from Yahoo Finance using the yfinance library.

🚀 Features

Fetches stock market data directly (no CSV required).

Preprocesses and scales historical closing prices.

Builds and trains an LSTM deep learning model.

Predicts future stock prices and compares with actual values.

Visualizes results with matplotlib.

📂 Project Structure
├── stock_prediction.ipynb   # Jupyter Notebook with full code
├── README.md                # Project documentation

🛠️ Installation

Clone this repo:

git clone https://github.com/K010208/stock-price-prediction.git
cd stock-price-prediction


Install required libraries:

pip install yfinance tensorflow scikit-learn matplotlib pandas

▶️ Usage

Open the Jupyter Notebook:

jupyter notebook stock_prediction.ipynb


Run all cells.

Change stock ticker symbol as needed:

df = yf.download("RELIANCE.NS", start="2018-01-01", end="2023-12-31")


Examples:

AAPL → Apple (US)

TSLA → Tesla (US)

RELIANCE.NS → Reliance Industries (India)

TCS.NS → TCS (India)

📊 Results

The model outputs a graph showing:

Training data

Actual stock prices

Predicted stock prices

Example visualization:

📚 Technologies Used

Python

yfinance – for stock data

TensorFlow / Keras – for LSTM model

scikit-learn – preprocessing

matplotlib – visualization

pandas, numpy – data handling

📌 Future Improvements

Add more ML models (Linear Regression, Random Forest, etc.).

Predict multiple steps ahead.

Build a Streamlit or Flask web app for live stock prediction.

👤 Author

GitHub: K010208
