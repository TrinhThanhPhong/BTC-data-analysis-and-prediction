# Bitcoin Price Prediction Analysis

This project analyzes and predicts Bitcoin prices using two different models: Prophet (Facebook's time series forecasting tool) and LSTM (Long Short-Term Memory neural network).

## Overview

The analysis uses historical Bitcoin price data to:
- Analyze price trends and patterns
- Visualize price movements and distributions
- Compare predictions from Prophet and LSTM models
- Predict future Bitcoin prices

## Dataset

The project uses daily Bitcoin price data including:
- Opening price
- Closing price
- High and low prices
- Trading volume

## Model Details

### Prophet Model
- Advantages:
  - Specifically designed for time series forecasting
  - Handles missing data and outliers well
  - Automatically detects seasonality patterns
  - Provides uncertainty intervals for predictions

- Limitations:
  - Works best with relatively stable time series
  - May not capture extreme market volatility
  - Requires sufficient historical data for accurate predictions

### LSTM Model
- Advantages:
  - Better at capturing complex patterns and non-linear relationships
  - Can learn long-term dependencies in the data
  - More suitable for highly volatile markets
  - Generally provides more accurate predictions for Bitcoin price

- Limitations:
  - Requires more data for training
  - More computationally intensive
  - Needs careful hyperparameter tuning
  - May be prone to overfitting

## Important Note
The Bitcoin market is highly volatile and influenced by various external factors such as:
- Market sentiment
- Regulatory news
- Global economic conditions
- Technological developments
- Institutional adoption

Due to these complex and unpredictable factors, even the most sophisticated prediction models may not provide accurate forecasts. The predictions should be used as one of many tools for market analysis, not as the sole basis for investment decisions.

## Project Structure
- `main.ipynb`: Main analysis and prediction notebook
- `BTC-Daily.csv`: Historical Bitcoin price dataset

## Results
The models' performance is evaluated using:
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

## Requirements
- Python 3.x
- Prophet
- TensorFlow/Keras
- Pandas
- NumPy
- Matplotlib
- Seaborn
- scikit-learn 