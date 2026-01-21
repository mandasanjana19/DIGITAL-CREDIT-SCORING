🚀 DIGITAL-CREDIT-SCORING
Machine Learning–Based Rural Credit Risk Assessment with Explainable AI

This repository contains a machine learning–powered platform for rural credit risk assessment and explainable credit scoring. The project focuses on improving financial inclusion for smallholder farmers and rural borrowers who often lack formal credit profiles.

🌱 Rural Credit Scoring Dashboard – Trustworthy AI for Financial Inclusion
📢 Project Overview

This project presents a machine learning–based rural credit scoring system designed to make lending decisions more accurate, transparent, and fair.
Multiple models were compared, and Explainable AI (SHAP) was integrated to help lenders understand why a borrower is classified as low or high risk.

The system is deployed as a Streamlit web application providing real-time, explainable credit predictions for rural lending.

📦 Repository Structure

App.py, app1.py - Main Streamlit application files

rural_credit_dataset_mixed.csv - Rural borrower dataset

xgb_model.pkl - Pre-trained XGBoost model

scaler.pkl, column_transformer.pkl - Feature preprocessing objects

graphs_paper1.py - Visualization scripts

newplot.jpg - Evaluation plots

Untitled.ipynb - EDA, preprocessing & model training notebook

image.jpeg, image.jpg - Dashboard screenshots

screenshots

🎯 Objectives

Build an accurate rural credit risk prediction system

Compare traditional and ensemble ML models

Improve model transparency using Explainable AI

Support fair and responsible lending

🧠 Models Implemented

Logistic Regression

Random Forest

XGBoost (Primary Model) ✅

⚙️ Tech Stack

Languages: Python

Libraries: Scikit-learn, XGBoost, SHAP, Pandas, NumPy, Matplotlib

Web App: Streamlit

Techniques: Standard Scaling, One-Hot Encoding, GridSearchCV, Ensemble Learning, Explainable AI

🗂️ Dataset & Preprocessing

Custom-built rural borrower dataset

Train-test split: 80% training / 20% testing

Preprocessing included:

Handling missing values

One-hot encoding of categorical features

Standard scaling of numerical features

Fixed random seeds for reproducibility

🔬 Experimental Setup

Evaluated Logistic Regression, Random Forest, and XGBoost

Applied GridSearchCV hyperparameter tuning for XGBoost

Evaluation metrics:

Accuracy

Precision

Recall

F1-score

ROC-AUC

Confusion Matrix

📊 Key Findings

🚀 XGBoost improved accuracy by ~18% over Logistic Regression

📈 Achieved the highest ROC-AUC score of 0.89

🎯 Reduced misclassification of risky borrowers

🔍 SHAP revealed top contributing features behind predictions

🧩 Explainable AI Integration (SHAP)

Implemented SHAP values for interpretability

Visualized:

Global feature importance

Individual borrower-level explanations

Improved trust, transparency, and fairness in credit decisions.

🌐 Deployment

Developed an interactive Streamlit web application.

Features:

Real-time credit risk prediction

Probability-based outputs

SHAP explanation plots

User-friendly interface for lenders

📈 Extending the Project

Add new models in App.py

Retrain models using the Jupyter notebook

Expand dataset with real-world rural data

Integrate advanced SHAP dashboards and simulations



<img width="568" height="801" alt="Screenshot 2025-11-12 234117" src="https://github.com/user-attachments/assets/257ea536-0eea-4692-b3d1-7dce02604e19" />


<img width="598" height="797" alt="Screenshot 2025-11-12 234309" src="https://github.com/user-attachments/assets/633b3234-ca51-49dc-b4c6-8aedf6d59f16" />


<img width="563" height="154" alt="Screenshot 2025-11-12 234422" src="https://github.com/user-attachments/assets/654f33ff-0dcc-4f7f-9bcb-feb775c0baef" />


<img width="544" height="403" alt="Screenshot 2025-11-12 234509" src="https://github.com/user-attachments/assets/2cc914a8-5a89-41b0-8b91-b35bab12a193" />
