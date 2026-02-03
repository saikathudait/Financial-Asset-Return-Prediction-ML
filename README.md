# Predictive Modeling of Financial Asset Returns

## Overview
This project focuses on predicting financial asset returns using machine learning techniques. Historical data on Stocks, Treasury Bills (T-Bills), and Treasury Bonds (T-Bonds) is analyzed to compare the performance of Linear Regression and Random Forest models.

The objective is to understand relationships between financial indicators and stock returns while evaluating model accuracy using statistical metrics.

## Dataset
- File: `Historicalinvesttemp.xlsx`
- Time span: 1928–2011
- Features:
  - Year
  - Stocks (returns)
  - T.Bills (returns)
  - T.Bonds (returns)

## Technologies Used
- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn
- Jupyter Notebook

## Methodology
1. Data loading and cleaning
2. Exploratory Data Analysis (EDA)
3. Feature engineering (normalization and lag features)
4. Model training:
   - Linear Regression
   - Random Forest Regressor
5. Model evaluation using:
   - Mean Squared Error (MSE)
   - R² Score

## Results
- Linear Regression performed better with lower error and higher R².
- Random Forest provided feature importance but showed weaker generalization due to limited data.

## Files in Repository
- `financial_market_analysis.py` – Full implementation of data analysis and models
- `Historicalinvesttemp.xlsx` – Historical financial dataset
- `README.md` – Project documentation

## How to Run
1. Install required libraries:
