# Cash Flow Forecasting

### Prepared by Dr. Omar A. Guerrero

This demo shows how to deploy the XGBoost machine learning algorithm to perform cash flow forecasting using time series data with a daily frequency.

### Data
Total daily deposits in the Treasury General Account of the United States of America. The frequency is daily and the coverage is from 1 January 2022 to 7 July 2026. The units are millions of USD. The source dataset can be downloaded here: https://fiscaldata.treasury.gov/datasets/daily-treasury-statement/deposits-and-withdrawals-of-operating-cash

### Requirements
The code was developed in Python version 3.12. The required libraries that need to be installed are:
- pandas (to load and manipulate the data)
- numpy (contains useful tools)
- matplotlib (to create plots)
- optuna (to fine tune the model)
- xgboost (provides the model to be trained)
- u8darts[all] (provides time series data structures and an interfacte for XGBoost that makes fine tuning easier; this interface is the same for other models beyond Darts)

### Running
To use the notebook online, load it using Binder by opening the link: https://mybinder.org/v2/gh/oguerrer/cash_forecasting_demo/HEAD
