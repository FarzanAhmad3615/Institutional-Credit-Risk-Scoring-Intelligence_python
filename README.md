# 💳 End-to-End Credit Risk IntelligenceDashboard (XGBoost)

An **institutional-grade credit risk modeling and visualization project** that demonstrates how machine learning can be applied to **loan default prediction** using realistic financial features and a modern analytics dashboard.

This project is designed to mirror **banking / fintech risk analytics workflows**, combining **data generation, gradient boosting, and executive-ready visual diagnostics**.

---

## 🚀 Project Overview

**Objective**
Build a robust credit risk classification model that predicts the **probability of loan default** and presents results through a **decision-focused visual dashboard** suitable for risk managers and analysts.

**Key Highlights**

* Realistic synthetic credit data with controlled default rates
* Gradient Boosting model using **XGBoost**
* Precision–Recall–focused evaluation (industry best practice)
* Business-oriented visual diagnostics

---

## 🧠 Business Context

In retail and corporate banking, default events are:

* **Rare but costly**
* **Highly asymmetric in risk impact**

Therefore, traditional accuracy metrics are insufficient. This project emphasizes:

* Recall of defaulters
* Precision–Recall trade-offs
* Probability score separation

---

## 🗂️ Dataset Description

Synthetic but **financially realistic** customer-level data is generated with the following features:

| Feature          | Description                   |
| ---------------- | ----------------------------- |
| `credit_score`   | Bureau score (300–850)        |
| `debt_to_income` | Debt burden ratio             |
| `loan_to_income` | Loan exposure vs income       |
| `years_at_job`   | Employment stability          |
| `is_default`     | Target variable (1 = Default) |

📌 **Default Rate:** 20% (intentionally enforced for model learning)

---

## ⚙️ Technology Stack

* **Python**
* **NumPy / Pandas** – Data handling
* **Matplotlib / Seaborn** – Visual analytics
* **Scikit-learn** – Evaluation metrics
* **XGBoost** – Gradient Boosting Classifier

---

## 🧪 Model Architecture

**Algorithm:** XGBoost Classifier
**Why XGBoost?**

* Handles non-linear risk relationships
* Strong performance on tabular financial data
* Interpretable feature importance

```python
XGBClassifier(
    n_estimators=100,
    max_depth=3,
    learning_rate=0.1,
    subsample=0.8
)
```

---

## 📈 Evaluation Strategy

### 1️⃣ Confusion Matrix

Provides a direct view of:

* False Negatives (missed defaulters)
* False Positives (rejected good customers)

### 2️⃣ Precision–Recall Curve ⭐

> Preferred over ROC in credit risk due to class imbalance

* Precision → Cost control
* Recall → Risk containment

### 3️⃣ Feature Importance

Identifies **key risk drivers** influencing default probability

### 4️⃣ Probability Distribution Analysis

Separates:

* Safe customers
* Defaulting customers

Used to define **cut-off thresholds** in production systems

---

## 📊 Visual Dashboard

The dashboard includes:

* Prediction Accuracy Matrix
* Precision–Recall Trade-off Curve
* Ranked Feature Importance
* Probability Density Comparison (Safe vs Default)

🎯 Designed for **executive decision-making**, not just model evaluation

---

## 🧾 Sample Model Output

```text
Precision    Recall    F1-score

Non-Default     High      High
Default         Strong    Strong

Overall: Balanced performance with clear probability separation
```

*(Exact values vary due to randomized data generation)*

---

## 🏦 Real-World Applications

* Loan approval automation
* Credit scorecard enhancement
* Risk-based pricing
* Early warning systems
* Regulatory stress testing prototypes

---

## 🔮 Possible Enhancements

* SHAP value explainability
* Cost-sensitive learning
* Calibration curves & PD adjustment
* Integration with real bureau datasets
* Deployment as a Streamlit / Dash app

---

## 👨‍💻 Author

**Farzan Ahmad**
Data Analytics & Financial Risk Modeling

📌 *Electronics & Communication Engineer | MSc Banking & Financial Analysis*
📌 *Aspiring Data Analyst / Risk Analyst*

---

## ⭐ Final Note

This project demonstrates **end-to-end credit risk intelligence**, blending:

* Statistical realism
* Machine learning rigor
* Business-oriented storytelling




<img width="918" height="299" alt="1cs" src="https://github.com/user-attachments/assets/db3c4b16-e855-42fa-aab1-6fb9d69df758" />
<img width="930" height="281" alt="2cs" src="https://github.com/user-attachments/assets/adcf2e5c-e271-403a-994d-3d01d28f8392" />



