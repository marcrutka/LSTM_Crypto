# 📈 Bitcoin Price Prediction using LSTM (Long Short-Term Memory)

## Overview
This project predicts Bitcoin prices using an **LSTM (Long Short-Term Memory) neural network**, a type of **Recurrent Neural Network (RNN)** designed for time-series forecasting. The model supports both **single-step and multi-step predictions**, forecasting BTC/USD prices up to 24 hours ahead.

## Features
✅ Fetches historical **BTC/USD** price data using Yahoo Finance  
✅ Preprocesses data with **MinMaxScaler** for better neural network performance  
✅ Implements **single-step** and **multi-step** forecasting  
✅ Uses an **LSTM model** to learn from past price movements  
✅ Visualizes **actual vs. predicted prices** with Matplotlib  
✅ Evaluates model performance using **MAE (Mean Absolute Error) and RMSE (Root Mean Squared Error)**  

## Technologies Used
- **Python** 🐍
- **TensorFlow/Keras** (LSTM model training)
- **scikit-learn** (data preprocessing & evaluation)
- **pandas & numpy** (data handling)
- **matplotlib** (data visualization)
- **Yahoo Finance API** (retrieving historical Bitcoin prices)

## Installation & Usage
1. **Clone the repository**
   ```bash
   git clone https://github.com/marcrutka/LSTM_Crypto.git
   cd LSTM_Crypto.ipynb
   ```
2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```
3. **Run the code**


## Example Prediction
![Predicted vs Actual](example.png)

## Disclaimer
This project is for **educational purposes only** and should not be used for financial decision-making. Cryptocurrency markets are highly volatile. Always conduct your own research before investing.



