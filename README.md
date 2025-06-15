# Bitcoin Price Prediction Analysis

This project analyzes and predicts Bitcoin prices using the Prophet model, a powerful time series forecasting tool developed by Facebook.

## Overview

The analysis uses historical Bitcoin price data to:
- Analyze price trends and patterns
- Visualize price movements and distributions
- Predict future Bitcoin prices using the Prophet model

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

## Project Structure
- `main.ipynb`: Main analysis and prediction notebook
- `BTC-Daily.csv`: Historical Bitcoin price dataset

## Results
The model's performance is evaluated using:
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

## Requirements
- Python 3.x
- Prophet
- Pandas
- NumPy
- Matplotlib
- Seaborn
- scikit-learn 