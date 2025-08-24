# Credit-Card-Fraud-Detection-with-Isolation-Forest

Overview

This project implements fraud detection using Isolation Forest on Kaggle data, focusing on imbalanced datasets.

Dataset





Source: Credit Card Fraud Detection on Kaggle



Description: 284,807 transactions with 31 features (Time, Amount, V1-V28, Class).



Distribution: Non-fraud (0): 284,315 (99.83%); Fraud (1): 492 (0.17%).

Files





fraud_detection.ipynb: Main notebook with code and analysis.



fraud_data_for_bi.csv: Processed data.



Visuals: class_distribution.png, amount_distribution.png, etc.

Results





ROC-AUC:



Classification Report:





Non-Fraud (0): Precision 1.00, Recall 1.00, F1 1.00



Fraud (1): Precision 0.33, Recall 0.34, F1 0.33



Key Insights: Model favors Non-Fraud; work in progress to improve Fraud detection.



Application: Potential for real-time fraud monitoring.

Installation





Clone: git clone <your-repo-url>



Install: pip install pandas numpy scikit-learn matplotlib seaborn joblib



Run the notebook.
