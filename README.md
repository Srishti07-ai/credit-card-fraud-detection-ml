# Credit Card Fraud Detection (ML Project)

## 📌 Overview
Detect fraudulent credit card transactions using machine learning.  
Because the dataset is highly imbalanced, we handle class imbalance and evaluate with recall-focused metrics.

## ⚙ Tech Stack
- Python · Pandas · NumPy  
- scikit-learn · XGBoost · imbalanced-learn  
- Matplotlib · Seaborn  
- Jupyter Notebook

## 🔍 Features
- Data cleaning and Z-score feature scaling  
- Class imbalance handling with *SMOTE* (and optional undersampling)  
- Models: *Logistic Regression, **Random Forest, **XGBoost*  
- Metrics: *Precision, Recall, F1-score, ROC-AUC*  
- Plots: Confusion Matrix and ROC curves

## 📊 Dataset
Kaggle: *Credit Card Fraud Detection*  
Link: https://www.kaggle.com/mlg-ulb/creditcardfraud

> Note: Do not upload the raw dataset to this repo if the license forbids it. Provide a link and loading instructions instead.

## 🚀 How to Run
1) Clone the repo
```bash
git clone https://github.com/your-username/credit-card-fraud-detection-ml.git
cd credit-card-fraud-detection-ml

pip install -r requirements.txt
jupyter notebook
