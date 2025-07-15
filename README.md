# 💳 Credit Card Fraud Detection – EDA Project

This repository contains a complete Exploratory Data Analysis (EDA) on anonymized credit card transactions.  
The goal is to understand how fraudulent transactions differ from legitimate ones using visual and statistical analysis.

---

## 📊 Dataset Information

- **Source**: [Kaggle: Credit Card Fraud Detection – Predictive Models](https://www.kaggle.com/code/gpreda/credit-card-fraud-detection-predictive-models/input)
- **Original Notebook Author**: [Gabriel Preda](https://www.kaggle.com/code/gpreda/)
- **Data Description**:
  - Total Records: 284,807 transactions
  - Features:
    - `Time`: seconds since first transaction
    - `Amount`: transaction amount
    - `V1` to `V28`: anonymized features from PCA
    - `Class`: target variable (0 = Legit, 1 = Fraud)

🟡 **Note**:  
The dataset is not redistributed here. You must download it from the Kaggle link above and save it as `creditcard.csv` in your local project directory to run the notebook.

---

## 📁 Files Included

| File Name                                 | Description                                  |
|------------------------------------------|----------------------------------------------|
| `EDA_CreditCardFraud_Explained_Final.ipynb` | Fully explained EDA notebook with step-by-step analysis |
| `README.md`                               | This project summary and usage instructions  |

---

## 🧠 What This EDA Covers

- ✅ What is EDA and why it’s important
- 📊 Dataset structure (`.shape`, `.info()`)
- ❓ Missing value analysis
- ⚠️ Class imbalance analysis of target variable (`Class`)
- 📈 Descriptive statistics for all features
- 🔗 Correlation matrix (heatmap)
- 📦 Boxplot comparison of key features (e.g., `V1`)
- 💵 Distribution of `Amount` and `Time` features
- ✅ Final summary with key takeaways

All steps are clearly explained, with Markdown cells describing what, why, and how each code block works.

---

## ⚙️ How to Use

1. Clone this repository
2. Download the dataset from Kaggle:
https://www.kaggle.com/code/gpreda/credit-card-fraud-detection-predictive-models/input

3. Place the file as creditcard.csv in the same directory as the notebook.

4. Run the notebook

🙌 Credits
Notebook Source Dataset: Gabriel Preda – Kaggle Notebook

Dataset Origin: European credit card transactions dataset (anonymized)

Purpose: Educational and academic use only

📌 License
This project is for non-commercial, educational purposes only.
All rights to the dataset and original predictive notebook belong to Gabriel Preda and Kaggle.



