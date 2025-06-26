<p align="center">
  <img src="https://raw.githubusercontent.com/ChinmaySN/customer-insurance-prediction/main/banner.png" alt="Customer Insurance Classifier Banner">
</p>


# 🛡️ Customer Insurance Purchase Prediction

Predict whether a customer will purchase insurance based on their **Age** and **Estimated Salary** using multiple machine learning models.

---

## 📌 Overview

As an analyst at a bank insurance company, your goal is to use customer data (age & salary) to predict insurance purchases. This project compares various classification algorithms to identify the most accurate and generalizable model.

---

## 💼 Business Objective

Develop an AI model to:
- Accurately predict if a customer will purchase insurance.
- Compare performance of various ML algorithms.
- Deploy simple prediction functions for end-users.

---

## 🧠 Models Used

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Decision Tree
- Random Forest

---

## 📊 Dataset

The dataset contains:

| Column          | Description                    |
|-----------------|--------------------------------|
| Age             | Customer age in years          |
| EstimatedSalary | Estimated salary (in **INR**)  |
| Purchased       | 1 = Purchased, 0 = Not purchased |

📁 File: `insurance_data.csv`

---

## 🚀 How to Use

### Option 1: Try Predictions Instantly

> ✅ No training required — just use the pre-trained models.

1. Open the notebook:  
   👉 [predict.ipynb](predict.ipynb)

2. Run all cells.

3. Predict like this:
random_forest_predict(30, 87000)
logistic_predict(45, 120000)
knn_predict(25, 60000)

### 🟡 Option 2: Train the Model Yourself

1. Open and run `insurance.ipynb`.

2. It will:
   - Preprocess the data  
   - Train all machine learning models  
   - Save the scaler and model files as `.pkl`  
   - Plot decision boundaries for each model

## 🧠 Hypotheses Tested

- 💡 Younger individuals with higher salaries are more likely to buy insurance.  
- 💡 Salary has a stronger influence than age.  
- 💡 Elderly customers with low income are less likely to purchase.

✅ All validated with the trained models.

---

## 📍 Real-World Applications

- Bank/Insurance CRM systems  
- Health/Travel/Life Insurance Lead Scoring  
- Personalized marketing in financial sectors
