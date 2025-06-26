<p align="center">
  <img src="https://raw.githubusercontent.com/ChinmaySN/customer-insurance-prediction/main/banner.png" alt="Customer Insurance Classifier Banner">
</p>


# Customer Insurance Prediction

Predict whether a customer will purchase insurance based on their age and estimated salary using various machine learning classification models.

---

## 📌 Project Overview

As an analyst at a bank-affiliated insurance company, your goal is to develop a predictive AI model using customer demographics (excluding personal identifiers) to identify potential insurance buyers. This helps improve targeting, reduce marketing costs, and boost conversions.

---

## 🔍 Problem Statement

Develop and compare multiple machine learning classification algorithms to:

- Predict insurance purchase decisions.
- Evaluate model performance across accuracy, precision, recall, F1-score, and ROC-AUC.
- Determine the most effective model that balances accuracy and generalization.

---

## 🧠 ML Algorithms Used

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Decision Tree Classifier
- Random Forest Classifier

---

## 📊 Dataset

Each record contains:

- `Age`: Customer's age
- `EstimatedSalary`: Annual income
- `Purchased`: 1 if the customer purchased insurance, else 0

*1000 rows of synthetic but realistic data were used for training and testing.*

---

## 📈 Results Snapshot

| Model                | Accuracy | Precision | Recall | F1-Score | ROC-AUC |
|---------------------|----------|-----------|--------|----------|---------|
| Random Forest        | 0.87     | 0.85      | 1.00   | 0.92     | 1.00    |
| SVM                  | 0.87     | 0.85      | 1.00   | 0.92     | 1.00    |
| Logistic Regression  | 0.87     | 0.85      | 1.00   | 0.92     | 1.00    |
| KNN                  | 0.87     | 0.85      | 1.00   | 0.92     | 0.88    |
| Decision Tree        | 0.87     | 0.85      | 1.00   | 0.92     | 0.75    |

---

## 📦 How to Use

1. Clone the repo:
```bash
git clone https://github.com/yourusername/customer-insurance-prediction
cd customer-insurance-prediction
