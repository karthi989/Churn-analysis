# 📉 End-to-End Customer Churn Prediction & Analytics Pipeline

An end-to-end Machine Learning and Business Intelligence solution designed to predict customer churn, uncover key behavioral drivers, and provide actionable insights for customer retention.

---

## 🚀 Project Overview
Customer churn is a critical challenge for subscription-based businesses. This project builds a full pipeline—from raw data processing and SQL analytics to machine learning modeling, explainable AI (LIME), interactive dashboards, and a live web deployment artifact.

---

## 🗂️ Dataset Source
* **Dataset:** Telco Customer Churn (cleaned & preprocessed as `churncleaned .csv`).
* **Records:** ~7,000+ customer entries.
* **Key Features:** Customer demographics, contract types, tenure, monthly/total charges, payment methods, and service usage flags.

---

## 🛠️ Tools & Tech Stack
* **Database / Querying:** SQL Server Management Studio (SSMS)
* **Data Processing & Modeling:** Python, Pandas, NumPy, Scikit-Learn (Random Forest, Pipelines)
* **Explainable AI:** LIME (Local Interpretable Model-Agnostic Explanations)
* **Business Intelligence:** Power BI (Interactive Dashboard)
* **Deployment/Persistence:** Joblib, Streamlit

---

## 🔄 How to Run Each Part of the Pipeline

### 1. SQL & Data Prep
* Load `churncleaned .csv` into your SQL database.
* Run exploratory queries to inspect customer segmentation, average charges by contract type, and churn ratios.

### 2. Python Modeling & Pipeline (`train.py`)
* Run the preprocessing, training, and evaluation script:
  ```bash
  python train.py
