# DIGITAL-CREDIT-SCORING
This repository contains a machine learning-powered platform for rural credit risk assessment and explainable credit scoring. The project is designed to improve financial inclusion for smallholder farmers and rural borrowers who often lack formal credit profiles.

Rural Credit Scoring Dashboard – Trustworthy AI for Financial Inclusion
📢 Project Overview
This project presents a machine learning–based rural credit scoring system designed to improve financial inclusion by making credit decisions more accurate, transparent, and fair.
We compared multiple classification models and integrated Explainable AI (SHAP) to help lenders understand why a borrower is classified as low or high risk.
The system is deployed as a Streamlit web application to provide real-time, explainable credit predictions for rural lending scenarios.

📦 Repository Structure
App.py, app1.py — Main Streamlit dashboard/application files. Run either to launch the user interface.

rural_credit_dataset_mixed.csv — Core dataset simulating real borrower profiles (demographics, agriculture, finance, digital behaviour).

xgb_model.pkl — Pre-trained XGBoost model for loan repayment prediction.

scaler.pkl, column_transformer.pkl — Data transformation objects (scaling and encoding features for consistency).

graphs_paper1.py, newplot.jpg — Visualisation code and sample output for use in reports or presentations.

Untitled.ipynb — Jupyter notebook for full exploratory data analysis, feature engineering, and model training.

image.jpeg, image.jpg — Dashboard screenshots and demo visuals for documentation/README use.
🎯 Objectives

Build an accurate credit risk prediction system for rural populations

Compare traditional and ensemble ML models

Improve model transparency using Explainable AI

Support fair and responsible lending decisions

🧠 Models Implemented

Logistic Regression

Random Forest

XGBoost (primary model)

⚙️ Tech Stack

Languages: Python

Libraries: Scikit-learn, XGBoost, SHAP, Pandas, NumPy, Matplotlib

Web App: Streamlit

Techniques: Standard Scaling, One-Hot Encoding, GridSearchCV, Ensemble Learning, Explainable AI

🗂️ Dataset & Preprocessing

Custom-built rural borrower dataset

Data split: 80% training / 20% testing

Preprocessing steps:

Handling missing values

One-hot encoding for categorical features

Standard scaling for numerical features

Fixed random seeds for reproducibility

🔬 Experimental Setup

Evaluated three classifiers: Logistic Regression, Random Forest, XGBoost

Applied hyperparameter tuning (GridSearchCV) for XGBoost

Performance evaluated using:

Accuracy

Precision

Recall

F1-score

ROC-AUC

Confusion Matrix

🔍 Key Findings

XGBoost improved accuracy by ~18% over Logistic Regression

Achieved the highest ROC-AUC (0.89), indicating strong class separation

Reduced misclassification of risky borrowers

SHAP visualizations revealed top contributing features behind every decision

🧩 Explainable AI Integration (SHAP)

Implemented SHAP values to interpret predictions

Visualized:

Feature importance

Individual prediction explanations

Improved trust, transparency, and fairness in lending decisions

🌐 Deployment

Built an interactive Streamlit web app

Features:

Real-time credit risk prediction

Probability-based output

SHAP explanation plots

User-friendly interface for non-technical lenders

📈 Extending the Project
Add new models to App.py or retrain using the Jupyter notebook.

Expand the dataset with real-world data for robust credit scoring.

Integrate live Monte Carlo scenarios or SHAP explainability modules.

<img width="568" height="801" alt="Screenshot 2025-11-12 234117" src="https://github.com/user-attachments/assets/257ea536-0eea-4692-b3d1-7dce02604e19" />


<img width="598" height="797" alt="Screenshot 2025-11-12 234309" src="https://github.com/user-attachments/assets/633b3234-ca51-49dc-b4c6-8aedf6d59f16" />


<img width="563" height="154" alt="Screenshot 2025-11-12 234422" src="https://github.com/user-attachments/assets/654f33ff-0dcc-4f7f-9bcb-feb775c0baef" />


<img width="544" height="403" alt="Screenshot 2025-11-12 234509" src="https://github.com/user-attachments/assets/2cc914a8-5a89-41b0-8b91-b35bab12a193" />
