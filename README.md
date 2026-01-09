# Coca-Cola Stock Price Forecasting

## Objective
Forecast daily closing prices of Coca-Cola stock using historical price data and
compare machine learning approaches for time-series regression.

## Dataset
- Daily OHLCV stock data
- Source: Yahoo Finance
- Period: 1962–2022

## Methodology
- Data cleaning and validation
- Feature engineering (lags, moving averages, volatility)
- Model comparison:
  - Linear Regression
  - Ridge, Lasso, Elastic Net
  - Random Forest, Gradient Boosting
- Residual diagnostics and error analysis

## Key Findings
- Regularized linear models outperform tree-based models
- Ridge Regression provides best stability and lowest error
- Residuals show volatility clustering but no systematic bias

## Business Use Case
- Long-term price tracking
- Scenario analysis
- Baseline forecasting for portfolio analytics

## Limitations
- No macro or fundamental data
- Not suitable for short-term trading

## Tools
Python, Pandas, NumPy, Scikit-learn, Matplotlib

