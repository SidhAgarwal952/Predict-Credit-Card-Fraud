# Predict-Credit-Card-Fraud
# 💳 Predict Credit Card Scam Using Machine Learning

This project focuses on building a machine learning model to identify and predict credit card scams (fraudulent transactions) based on patterns in transaction data such as amount, time, and anonymized features. The goal is to assist financial institutions in minimizing losses by accurately flagging suspicious activity.

---

## 📁 Dataset Overview

- **Source**: Real-world anonymized credit card transactions
- **Records**: 284,807 transactions
- **Fraud Cases**: 492 (≈0.17%)
- **Features**:
  - `V1` to `V28`: PCA-transformed features (to protect confidentiality)
  - `Time`: Seconds elapsed between this transaction and the first transaction
  - `Amount`: Transaction amount
  - `Class`: Target label (`0` = genuine, `1` = scam)

---

## 🧰 Tools & Technologies

- **Language**: Python
- **Libraries**: 
  - `Pandas`, `NumPy` – data manipulation
  - `Scikit-learn` – machine learning models and metrics
  - `Matplotlib`, `Seaborn` – visualizations

---

## 🔍 Key Features

- Data preprocessing and standardization
- Handling class imbalance using `class_weight='balanced'`
- Random Forest classification model
- Evaluation with:
  - Confusion Matrix & Heatmap
  - Classification Report (precision, recall, F1-score)
  - ROC-AUC Score

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/your-username/predict-credit-card-scam.git
cd predict-credit-card-scam
