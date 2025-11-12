# DIGITAL-CREDIT-SCORING
This repository contains a machine learning-powered platform for rural credit risk assessment and explainable credit scoring. The project is designed to improve financial inclusion for smallholder farmers and rural borrowers who often lack formal credit profiles.


Rural Credit Scoring Dashboard – Trustworthy AI
A practical, explainable, and fair AI solution for automated rural credit risk assessment.
This repository provides a complete workflow from dataset preparation and advanced ML model training to an interactive credit scoring dashboard ready for end-user deployment.

🌟 Project Overview
Millions of rural borrowers and farmers in India struggle to access fair credit due to lack of formal financial history and opaque assessment methods. The aim of this project is to build a Trustworthy AI system that predicts rural loan repayment risk, gives a clear credit score, and explains its reasoning for each borrower.

Key Features:

Data-driven, real-world inspired rural credit scoring workflow

Interactive dashboard for lenders or researchers

Model explanations: shows which features matter most (trust and fairness)

Built using state-of-the-art models (Logistic Regression, Random Forest, XGBoost)

📁 Repository Contents
App.py, app1.py – Main Python source files for the interactive Streamlit dashboard/application.

rural_credit_dataset_mixed.csv – The full synthetic dataset of borrower profiles and loan status.

xgb_model.pkl – Trained XGBoost model for loan risk prediction (ready to deploy).

scaler.pkl, column_transformer.pkl – Saved preprocessing transformers for consistent feature scaling and encoding.

graphs_paper1.py, newplot.jpg – Scripts and images for visualizations in reports/papers.

Untitled.ipynb – Jupyter notebook for data exploration, modelling, and EDA.

image.jpeg, image.jpg – Dashboard output screenshots for documentation or reference.

⚙️ How to Deploy This Project
Clone the repository

bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
Install dependencies
Required packages:

streamlit

pandas

scikit-learn

xgboost

matplotlib

bash
pip install -r requirements.txt
# or, to install individually:
pip install streamlit pandas scikit-learn xgboost matplotlib
Run the Dashboard

bash
streamlit run App.py
The app will open in your browser.

Edit user profile fields and instantly see updated predictions and explanations.

Explore the Code

App.py or app1.py shows the logic for loading saved models, user input forms, and displaying risk metrics.

Untitled.ipynb provides data exploration, training pipeline, and reproducibility for experiments.

ML models and processing transformers are loaded automatically.

Customizing/Training

Use the Jupyter notebook to retrain ML models or add new features to the dataset.

Replace trained models (xgb_model.pkl) if you want to use your own.

💡 Project Highlights
Explainable AI: Dashboard not only predicts scores but shows why—feature importance plots make results easy to trust.

Trustworthy Workflow: Bias-safe, fair, with reproducible ML pipeline.

Rural Relevance: Factors in real farming features: land size, crop, digital activity, and more.

🚀 Demo Use Case
See the included screenshots for a sample Maharashtra farmer profile.

Review the credit risk output and the graph highlighting land size as a dominant positive factor.
