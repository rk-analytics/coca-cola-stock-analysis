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

## Key Results
- Ridge Regression closely tracks actual closing prices across the full time horizon.
- RMSE and MAE indicate stable predictive performance on unseen data.
- Residuals are centered around zero, confirming the model is unbiased.
- Residual variance increases during high-volatility periods (e.g., 2020), highlighting market regime effects.

## Business Use Case
- Long-term price tracking
- Scenario analysis
- Baseline forecasting for portfolio analytics

## Limitations
- No macro or fundamental data
- Not suitable for short-term trading

## Tools
Python, Pandas, NumPy, Scikit-learn, Matplotlib

## Repository Structure

- **Coca-Cola_stock_history.csv**  
  Historical daily stock price data used for modeling and analysis.

- **coca_cola_stock_analysis.ipynb**  
  End-to-end data analysis and Ridge Regression modeling notebook.

- **tableau_stock_model_output.csv**  
  Model predictions and residuals exported for Tableau visualization.

- **Stock_Price_Prediction_Ridge_Regression.twbx**  
  Interactive Tableau dashboard for model evaluation and residual diagnostics.


