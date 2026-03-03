Fraud Transaction Detection using Machine Learning

Overview
This project builds a fraud detection system using financial transaction data.
The model handles highly imbalanced data and predicts fraudulent transactions.

Dataset
Kaggle PaySim Fraud Dataset
(Class imbalance: ~0.1% fraud cases)

Techniques Used
Feature Engineering (amount ratio, emptied account flag)
Logistic Regression / Random Forest
Class weighting
Precision-Recall Optimization
Threshold tuning
Streamlit deployment

Model Performance
ROC-AUC: XX
Recall (Fraud): XX
Precision (Fraud): XX

Deployment
Run locally:
streamlit run fraud_detection.py

Tech Stack
Python
Scikit-learn
Pandas
Streamlit

Kaggle Dataset: https://www.kaggle.com/datasets/amanalisiddiqui/fraud-detection-dataset