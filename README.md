# Credit-Card-Fraud-Detection-with-Isolation-Forest
Overview

This project implements fraud detection using Isolation Forest on Kaggle data, emphasizing EDA, modeling, and evaluation.

Dataset





Source: Credit Card Fraud Detection on Kaggle



Description: 284,807 transactions with 31 features (Time, Amount, V1-V28, Class).



Distribution: Non-fraud (0): 284,315 (99.83%); Fraud (1): 492 (0.17%).

Files





fraud_detection.ipynb: Main notebook with code and analysis.



fraud_data_for_bi.csv: Processed data.



Visuals: class_distribution.png, amount_distribution.png, amount_boxplot.png, scatter_amount_time.png, confusion_matrix.png, decision_scores.png, feature_importance.png.

Results





ROC-AUC: ~0.95



Classification Report: High recall for fraud (~0.85), suitable for imbalanced data.



Key Insights: Frauds have lower amounts and cluster in specific times. V14, V12, V10 most important features.



Application: Real-time fraud monitoring.

Installation





Clone: git clone <your-repo-url>



Install: pip install pandas numpy scikit-learn matplotlib seaborn joblib



Run the notebook on Kaggle or locally.
