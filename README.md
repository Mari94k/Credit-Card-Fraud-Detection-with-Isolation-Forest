# Credit Card Fraud Detection 📊💳

## Overview 🌟
This project detects credit card fraud using **Isolation Forest**, **Random Forest**, **XGBoost**, and **Decision Tree**. It handles imbalanced data, shows results with charts, and includes a Flask API (needs local setup). XGBoost is the best model with top ROC-AUC and Recall, with Decision Tree adding a simpler approach. 🚀

## Features ✨
- Preprocesses data
- Compares models with charts
- Includes API code (local setup needed)
- Saves models

## Installation 🛠️
- Clone the repo and install dependencies (see below).
- Get creditcard.csv from [Kaggle](https://www.kaggle.com/mlg-ulb/creditcardfraud).
git clone https://github.com/your-username/credit-card-fraud-detection.git
pip install pandas numpy scikit-learn xgboost matplotlib seaborn flask joblib

## Usage 🎯
- Open Credit_Card_Fraud_Detection.ipynb in Jupyter or Kaggle and run "Run All".
- For API, save code as predict_api.py and run it locally (details in notebook).
pip install flask joblib
python predict_api.py
- Test with a POST request to http://localhost:5000/predict

## Dependencies 📦
- pandas
- numpy
- scikit-learn
- xgboost
- matplotlib
- seaborn
- flask
- joblib
(Create requirements.txt with pip freeze > requirements.txt)

## Files 📑
- Credit_Card_Fraud_Detection.ipynb: Main notebook
- predict_api.py: API code
- *.pkl: Saved models
- fraud_data_for_bi.csv: Data

## Results 📈
- Isolation Forest: Moderate
- Random Forest: Balanced
- XGBoost: Best with highest ROC-AUC and Recall
- Decision Tree: Simple model, moderate performance
(See model_comparison.png or notebook)
