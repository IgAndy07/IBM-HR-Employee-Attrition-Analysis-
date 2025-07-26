# 🧑‍💼 IBM HR Attrition Analysis

## 📌 Overview

This project explores employee attrition patterns using the **IBM HR Analytics Employee Attrition & Performance** dataset. It includes exploratory data analysis (EDA), feature engineering, and machine learning to predict employee attrition based on various demographic and job-related factors.

---

## 🎯 Objectives

- Identify key factors influencing employee attrition.
- Visualize relationships between attrition and features like age, gender, income, and job level.
- Build and evaluate machine learning models to predict attrition.

---

## 🗃️ Dataset

- Source: IBM HR Analytics (available on Kaggle)
- Target Variable: `Attrition`
- Notable Features:
  - `Age`, `Gender`, `MonthlyIncome`, `JobLevel`
  - `YearsAtCompany`, `YearsInCurrentRole`
  - `JobRole`, `OverTime`, `BusinessTravel`

---

## 🔍 Key Insights from EDA

- Attrition is highest for employees aged **18 to 35**.
- **Higher income** is correlated with **lower attrition**.
- **Divorced women** show significantly lower attrition rates.
- Employees with frequent **business travel** tend to leave more.
- Certain job roles (e.g. **Sales Expert**, **Level 1 roles**) see higher attrition.
- Strong feature correlations were found, such as:
  - `MonthlyIncome` ↔ `JobLevel`
  - `YearsInCurrentRole`, `YearsAtCompany`, `YearsWithCurrentManager`

---

## 🤖 Machine Learning Models

| Model                | Accuracy |
|---------------------|----------|
| Logistic Regression | 76%      |
| Random Forest       | 98% ✅    |

> Balanced classification techniques and robust scaling were used to handle class imbalance and improve model performance.

---

## 🛠️ Tech Stack

- **Language:** Python
- **Libraries:**
  - `pandas`, `numpy`, `seaborn`, `matplotlib`
  - `scikit-learn`, `imbalanced-learn`
  - `LabelEncoder`, `RobustScaler`

---

