# Customer Churn Prediction

An end-to-end machine learning project that predicts whether a telecom customer is likely to churn based on customer demographics, services, contract details, tenure, and billing information.

## Project Overview

Customer churn is an important business problem for telecom companies because identifying customers who are likely to leave can help businesses take preventive retention actions.

This project develops a machine learning pipeline to:

- Clean and preprocess customer data
- Perform exploratory data analysis
- Engineer relevant features
- Train multiple classification models
- Compare model performance
- Analyze prediction thresholds
- Identify important churn-related features
- Deploy the final model using Streamlit

## Dataset

The project uses the IBM Telco Customer Churn dataset.

- Records: 7,043 customers
- Target variable: `Churn Label`
- Classes:
  - `No`
  - `Yes`

The dataset contains customer demographic, service, contract, and billing information.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib
- Seaborn
- Streamlit
- Joblib

## Machine Learning Workflow

```text
Raw Dataset
     ↓
Data Cleaning
     ↓
Exploratory Data Analysis
     ↓
Feature Engineering
     ↓
Train/Test Split
     ↓
One-Hot Encoding + Standard Scaling
     ↓
Model Training
     ↓
Model Evaluation
     ↓
Cross-Validation
     ↓
Feature Importance
     ↓
Final Random Forest Model
     ↓
Model Serialization
     ↓
Streamlit Application