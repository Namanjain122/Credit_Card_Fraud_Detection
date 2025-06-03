# Credit_Card_Fraud_Detection
# 💳 Credit Card Fraud Detection

This project focuses on detecting fraudulent credit card transactions using machine learning. Two models are implemented:
- **Linear Regression**
- **Random Forest Classifier**

Among these, the **Random Forest model gives the best accuracy and performance** in identifying fraud.

---

## 📂 Dataset

The dataset used is the **Credit Card Fraud Detection dataset** available from [Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud), which contains transactions made by European cardholders in September 2013.

- **Number of records**: 284,807
- **Features**: 30 (including `Time`, `Amount`, and 28 PCA-transformed features `V1` to `V28`)
- **Target**: `Class` (0 = Non-fraud, 1 = Fraud)

---

## 🧠 Machine Learning Models

### 1. Linear Regression
- Used as a baseline model.
- Applied with threshold tuning.
- Performance is limited due to linear nature and the imbalanced dataset.

### 2. Random Forest Classifier
- Ensemble method using multiple decision trees.
- Handles imbalanced data and nonlinear patterns effectively.
- Provided **the best accuracy, precision, recall, and F1-score**.

---

## 🧪 Evaluation Metrics

Given the imbalanced dataset, accuracy alone is not enough. The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- ROC-AUC Score

---

## 🥇 Results

| Model              | Accuracy | Precision | Recall | F1 Score | ROC-AUC |
|-------------------|----------|-----------|--------|----------|---------|
| Linear Regression | 91.5%    | 0.35      | 0.12   | 0.18     | 0.84    |
| Random Forest     | **99.9%**| **0.97**  | **0.91**| **0.94** | **0.99**|

✅ **Random Forest significantly outperforms Linear Regression** in detecting fraud cases.



