# 📈 Customer Churn Prediction

## 🔍 Project Overview
This project aims to predict customer churn for a telecom company using machine learning. By analyzing customer demographics, service usage, and account details, we identify patterns that signal potential churn. The goal is to help businesses take proactive retention measures and reduce customer loss.

## 📊 Dataset Source
- **Name**: Telco Customer Churn
- **Rows**: 7,043 customers
- **Columns**: 21 features including demographics, services, billing, and churn status
- **Source**: [Kaggle – Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

## 🧰 Tech Stack
- **Language**: Python
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Tools**: Jupyter Notebook, Git, GitHub
- *(Power BI dashboard planned for Phase 2)*

## 📈 Exploratory Data Analysis (EDA)
- Visualized churn distribution across tenure, contract type, and payment method
- Identified key drivers of churn: short tenure, month-to-month contracts, high monthly charges
- Created correlation heatmaps and feature importance plots

## 🤖 Modeling Approach
- Preprocessing: handled missing values, encoded categorical features
- Models used: Logistic Regression, Random Forest, XGBoost
- Evaluation metrics: Accuracy, Precision, Recall, F1 Score, ROC-AUC

## 📊 Results
- Best model: **Random Forest**
- ROC-AUC: **0.85**
- Confusion Matrix and ROC Curve included in `notebooks/churn_modeling.ipynb`

## 💼 Business Impact
- Enables telecom companies to identify high-risk customers early
- Supports targeted retention campaigns
- Potential to reduce churn rate and improve customer lifetime value

## 🗂️ Project Structure
