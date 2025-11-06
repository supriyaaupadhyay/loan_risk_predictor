# loan_risk_predictor
Loan Default Risk Prediction Model

Overview

This project demonstrates an end-to-end data science pipeline focused on solving a critical problem in the financial industry: predicting the probability of a loan applicant defaulting. The core deliverable is a risk score, which banks can use to make informed lending decisions.

The model is built using a simulated dataset and employs a Logistic Regression classifier for its inherent interpretability.

Key Features

Data Simulation: Generates a synthetic dataset of 10,000 loan applicants with features like Income, Credit Score, DTI, and Loan Amount.

Data Preprocessing: Implements a scikit-learn pipeline for standardizing numerical features and one-hot encoding categorical features.

Binary Classification: Uses a Logistic Regression model trained to predict the binary target (Default).

Model Evaluation: Reports key classification metrics, including AUC, Precision, Recall, and the Confusion Matrix.

Model Interpretability: Extracts and interprets feature coefficients to explain which factors (e.g., Credit Score, DTI) drive the risk score up or down, fulfilling the need for transparency in financial modeling.

Skills Demonstrated

Python (Pandas, NumPy, Scikit-learn)

Binary Classification

Feature Engineering & Pipelines (ColumnTransformer)

Model Evaluation & Selection

Model Interpretability (Coefficient Analysis)
