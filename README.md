# 🏦 Credit Risk Scoring – Banking ML Project

## Overview
This project predicts customer loan default risk using the German Credit dataset.  
The model is trained with Random Forest and XGBoost, and deployed in an interactive Streamlit dashboard.

## Dataset
- Source: [German Credit Data (UCI / Kaggle)](https://www.kaggle.com/datasets/uciml/german-credit)
- 1000 records, 20 features, binary classification (good vs bad credit risk).

## Features
- Data preprocessing (categorical encoding, scaling)
- Machine learning classification
- Model evaluation (ROC-AUC, F1-score)
- Interactive Streamlit dashboard for real-time scoring

## Run
```bash
pip install -r requirements.txt
streamlit run app/streamlit_app_banking.py
