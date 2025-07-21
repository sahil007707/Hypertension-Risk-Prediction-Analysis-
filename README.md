# 🩺 Hypertension Risk Prediction using Machine Learning

This project focuses on building a data-driven machine learning model to predict the risk of **hypertension (high blood pressure)** based on key health indicators and demographic features. By leveraging medical data, we aim to assist in early diagnosis and prevention strategies through predictive analytics.

---

## 📚 Table of Contents

- [📍 Objective](#-objective)
- [📦 Dataset Overview](#-dataset-overview)
- [🧼 Data Cleaning & Preprocessing](#-data-cleaning--preprocessing)
- [📊 Exploratory Data Analysis (EDA)](#-exploratory-data-analysis-eda)
- [🧠 Machine Learning Models](#-machine-learning-models)
- [📈 Evaluation & Metrics](#-evaluation--metrics)
- [🛠️ Tools Used](#-tools-used)
- [🚀 Future Work](#-future-work)
- [📁 Project Structure](#-project-structure)
- [📬 Contact](#-contact)

---

## 📍 Objective

Hypertension is a leading cause of heart disease and stroke worldwide. This project aims to:

- Analyze health-related factors that contribute to hypertension.
- Develop a predictive model to assess an individual’s risk level.
- Deliver insights that can aid in preventive healthcare decisions.

---

## 📦 Dataset Overview

The dataset includes information about individuals such as:

- **Age**
- **BMI (Body Mass Index)**
- **Physical Activity**
- **Smoking & Alcohol Habits**
- **Medical Conditions (e.g., Diabetes, Heart Disease)**
- **Gender, Sleep Duration, Work Type, Stress Levels**

🧠 **Target Variable:**  
`Hypertension` (0: No, 1: Yes)

---

## 🧼 Data Cleaning & Preprocessing

Steps performed:

- ✅ Handled missing values using statistical imputation
- 🧹 Converted categorical variables using label and one-hot encoding
- ⚖️ Handled class imbalance (if any) using techniques like SMOTE
- 🧮 Feature scaling applied using StandardScaler

---

## 📊 Exploratory Data Analysis (EDA)

Key insights from EDA:

- 📈 Higher BMI correlates strongly with hypertension risk
- 🔥 Smoking and alcohol intake increase hypertension likelihood
- 👵 Older individuals and those with heart disease are more vulnerable
- 💤 Very low or very high sleep durations also associate with increased risk

Visuals included:

- Distribution plots
- Box plots
- Heatmaps of feature correlations
- Age & BMI trends by hypertension status

---

## 🧠 Machine Learning Models

Several classification models were built and evaluated:

| Model                  | Accuracy | Precision | Recall | F1 Score |
|------------------------|----------|-----------|--------|----------|
| Logistic Regression    | ✓        | ✓         | ✓      | ✓        |
| Random Forest Classifier | ✓✓       | ✓✓        | ✓✓     | ✓✓       |
| XGBoost Classifier     | ⭐ Best  | ⭐ Best   | ⭐ Best| ⭐ Best  |

✅ **XGBoost** provided the best overall performance with strong generalization on unseen data.

---

## 📈 Evaluation & Metrics

- Confusion Matrix
- ROC-AUC Score
- Precision-Recall Curve
- Cross-validation for robustness

**Goal:** Minimize false negatives to avoid misclassifying high-risk individuals.

---

## 🛠️ Tools Used

- **Python** 🐍
- **Pandas & NumPy** — Data wrangling
- **Matplotlib & Seaborn** — Visualization
- **Scikit-learn** — Machine Learning & preprocessing
- **XGBoost** — Gradient boosting classifier

---

## 🚀 Future Work

To improve and extend the project:

- Integrate external factors (diet, salt intake, family history)
- Use explainability tools like **SHAP** or **LIME**
- Build a simple web app using **Streamlit** for real-time prediction
- Explore deep learning models for richer feature interactions

---


