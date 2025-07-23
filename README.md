
#  Telecom Customer Churn Prediction

This project aims to predict customer churn for a telecom company using machine learning. By analyzing customer demographics, contract details, and service usage, we identify the key factors leading to churn and recommend strategies to improve customer retention.

---

##  Dataset Description

The **Telco Customer Churn dataset** includes 7,032 customer records with information on:
- Demographics (gender, senior status)
- Account information (contract type, payment method)
- Services used (internet, streaming, tech support)
- Target: `Churn` (Yes/No)

**Source:** [Kaggle: Telco Customer Churn by Blastchar](https://www.kaggle.com/blastchar/telco-customer-churn)

---

##  Problem Overview

The goal is to predict which customers are likely to churn based on historical account and service usage data. This enables proactive action to reduce churn and improve business performance.

---

##  Key Insights

- **Churn Rate:** ~26% of customers
- **Best Model:** Logistic Regression (F1 Score = 0.61)
- **Top Churn Factors (via SHAP):**
  - Month-to-month contracts
  - Low customer tenure
  - High monthly charges
  - Electronic check payment method

---

## 🧠 Model Comparison

| Model             | Accuracy | Precision (Churn=1) | Recall (Churn=1) | F1 Score (Churn=1) |
|------------------|----------|----------------------|------------------|--------------------|
| Logistic Reg.     | 0.77     | 0.55                 | 0.63             | 0.59               |
| Random Forest     | 0.78     | 0.58                 | 0.56             | 0.57               |
| XGBoost           | 0.75     | 0.52                 | **0.70**         | **0.60**           |

---

## 📌 Business Recommendations

- Encourage customers to switch to **long-term contracts**
- Offer **discounts for high monthly bill customers**
- Improve onboarding and support for **new customers (low tenure)**
- Promote **auto-pay options** over electronic check



---

## ▶️ Try it Yourself

> 📌 **Open in Google Colab:**
> [Click here to run the project in Colab](https://colab.research.google.com/drive/1xNDJ5nBXPVn6N27yHdB3abtEe5CCiiLu?usp=sharing)

---


