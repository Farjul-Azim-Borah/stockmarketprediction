# Stock Market Prediction

## Overview
This project focuses on predicting stock market trends using machine learning techniques, specifically Long Short-Term Memory (LSTM) models. The goal is to analyze historical stock data and forecast future prices.

## Features
- **LSTM-based Prediction**: Utilizes deep learning models to predict stock prices.
- **Streamlit Web App**: Provides an interactive interface for users to input stock data and view predictions.
- **Development Container Support**: Ensures a consistent development environment.

## Installation
### Prerequisites
Ensure you have Python installed (preferably Python 3.8+).

### Clone the Repository
```sh
git clone https://github.com/Farjul-Azim-Borah/stockmarketprediction.git
cd stockmarketprediction
```

### Install Dependencies
```sh
pip install -r requirements.txt
```

## Usage
### Running the Streamlit App
```sh
streamlit run streamlit_app.py
```
This will launch a local server where you can interact with the stock prediction model.

### Running the Model Manually
```sh
python market.py
```
Modify `market.py` to use your dataset for training and testing.

## Project Structure
```
📂 stockmarketprediction
├── 📂 .devcontainer    # Development container configuration
├── 📄 Stock_LSTM_Model_Next_3_Months.keras  # Trained LSTM model
├── 📄 Stock_prediction_model.keras  # Another trained model
├── 📄 market.py  # Core logic for stock price prediction
├── 📄 streamlit_app.py  # Streamlit-based interactive UI
├── 📄 requirements.txt  # List of dependencies
└── 📄 README.md  # Project documentation
```

## Dataset
This project requires historical stock market data. You can use sources like:
- Yahoo Finance ([https://finance.yahoo.com/](https://finance.yahoo.com/))
- Alpha Vantage ([https://www.alphavantage.co/](https://www.alphavantage.co/))


