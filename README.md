




# Bitcoin-Price-Forecasting-with-Hybrid-LSTM-ARIMA-A-Data-Driven-Approach
🪙 Bitcoin Price Analysis using HMM, Hybrid LSTM & ARIMA

📌 Project Overview

This final year project focuses on analyzing and predicting Bitcoin prices using a combination of statistical and deep learning models:

* Hidden Markov Models (HMM)
* Hybrid Long Short-Term Memory Networks (LSTM)
* AutoRegressive Integrated Moving Average (ARIMA)

The goal is to compare the accuracy of these models in forecasting Bitcoin price trends using historical data.

🧠 Technologies Used

* Python
* NumPy, Pandas
* Matplotlib, Seaborn
* hmmlearn
* TensorFlow / Keras
* statsmodels
* scikit-learn

 📊 Dataset

* Source: Yahoo Finance
* Data: Daily Bitcoin price (Open, High, Low, Close, Volume)
* Duration: Customizable using script

🔍 Methodology

1. Data Preprocessing

   * Handling missing values
   * Normalization
   * Feature engineering (returns, log returns)

2. Hidden Markov Model (HMM)

   * Apply HMM on log returns
   * Identify hidden states or market regimes
   * Visualize regime shifts

3. Hybrid LSTM Model

   * Create time-series sequences
   * Train an LSTM network with dense layers
   * Evaluate with RMSE, MSE

4. ARIMA Model

   * Check stationarity using ADF test
   * Identify (p,d,q) using ACF/PACF plots
   * Forecast prices and compare metrics
