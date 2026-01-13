# 💳 Credit Card Fraud Detection (Classification)

## 📌 Project Overview
Credit card fraud is a major issue in the financial sector. The goal of this project is to **detect fraudulent credit card transactions** using machine learning classification algorithms.

The dataset is **highly imbalanced**, making traditional accuracy metrics unreliable. Therefore, we focus on metrics such as **Precision, Recall, F1-Score, and AUPRC (Area Under Precision-Recall Curve)**.

---

## 📂 Dataset Information
- **Source:** Kaggle – Credit Card Fraud Detection  
- **Link:** https://www.kaggle.com/mlg-ulb/creditcardfraud  

### Dataset Description
- Transactions made by **European cardholders** in September 2013
- Covers transactions over **2 days**
- **Total transactions:** 284,807  
- **Fraudulent transactions:** 492  
- **Fraud ratio:** 0.172%

### Features
- **V1 – V28:** PCA-transformed numerical features (confidential)
- **Time:** Seconds elapsed since the first transaction
- **Amount:** Transaction amount
- **Class:** Target variable  
  - `1` → Fraud  
  - `0` → Normal transaction

> ⚠️ Due to confidentiality, original feature meanings are not available.

---

## ⚖️ Class Imbalance
The dataset is **extremely imbalanced**, so:
- Accuracy is **not a reliable metric**
- Confusion Matrix alone is **misleading**
- Preferred evaluation metrics:
  - Precision
  - Recall
  - F1 Score
  - **AUPRC (recommended)**

---

## 🧰 Libraries Used
```bash
pandas
matplotlib
seaborn
scikit-learn

Best Model F1 Score: 87.00
