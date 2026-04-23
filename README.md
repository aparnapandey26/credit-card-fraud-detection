# 💳 Credit Card Fraud Detection

## 📌 Project Overview
This project is a **Machine Learning-based Fraud Detection System** that identifies whether a credit card transaction is **fraudulent or legitimate**.

The system uses historical transaction data and predicts fraud in real-time.


## ❗ Problem Statement
Credit card fraud is a major issue in the financial sector.

The goal is to detect:
- Fraudulent transaction (1)
- Legitimate transaction (0)

---

## 🧠 Machine Learning Workflow
- Data Collection
- Data Cleaning
- Handling Class Imbalance 
- Feature Scaling (StandardScaler)
- Model Training
- Model Evaluation
- Deployment using Streamlit

---

## 🤖 Model Used
Random Forest / XGBoost

### Input Features:
- Transaction Amount
- Time
- PCA-transformed features (V1, V2, ... V28)

### Output:
- `1 → Fraud Transaction`
- `0 → Legitimate Transaction`

---

## ⚙️ Tech Stack
- Python 🐍
- Pandas 📊
- NumPy 📦
- Scikit-learn 🤖

How to Run Locally

### 1. Clone repository
bash
git clone https://github.com/your-username/Credit_Card_Fraud_Detection.git
cd Credit_Card_Fraud_Detection

### Author
Aparna Pandey
