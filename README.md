# saaS-churn-prediction
# 🔄 SaaS Churn Prediction

## 📌 Problem Statement
Predict which customers are likely to cancel their 
subscription so the business can take action early.

## 📊 Dataset
- Source: Kaggle Telco Customer Churn
- Rows: 7043 customers
- Target: Churn (Yes/No)

## 🛠️ Tech Stack
- Python, Pandas, NumPy
- Scikit-learn, XGBoost, LightGBM
- SHAP (Explainability)
- FastAPI (Backend)
- Streamlit (Dashboard)
- Docker (Deployment)

## 📁 Project Structure
## 📁 Project Structure

saas-churn-prediction/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   ├── 01_EDA.ipynb
│   ├── 02_preprocessing.ipynb
│   ├── 03_model_building.ipynb
│   ├── 04_model_evaluation.ipynb
│   └── 05_shap_explainability.ipynb
│
├── src/
│   ├── __init__.py
│   ├── data_preprocessing.py
│   ├── feature_engineering.py
│   ├── model_training.py
│   └── predict.py
│
├── models/
│   └── xgboost_model.pkl
│
├── app/
│   └── app.py
│
├── dashboard/
│   └── streamlit_app.py
│
├── tests/
│   └── test_predict.py
│
├── .gitignore
├── requirements.txt
├── README.md
└── Dockerfile
## 🚀 How to Run
(add steps to run locally)

## 📈 Results
- Best Model: XGBoost
- ROC-AUC Score: 0.85
- Precision: 0.80

## 👤 Author
BY B. Navya sree
