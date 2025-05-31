# 🛡️ Phishing Email Detection using Machine Learning

This project aims to detect phishing emails using machine learning techniques, with a focus on handling class imbalance and optimizing recall. The dataset consists of binary-labeled emails (0 = non-phishing, 1 = phishing), and the goal is to minimize false negatives (i.e., undetected phishing emails).

## 📌 Features

- Binary classification: Phishing (1) vs. Non-Phishing (0)
- Extensive data exploration and feature distribution analysis
- Class imbalance handled using:
  - Class weighting (`class_weight='balanced'`)
  - SMOTE / ADASYN oversampling
- Models implemented:
  - Logistic Regression
  - Random Forest
- Evaluation using Precision-Recall metrics and confusion matrix
