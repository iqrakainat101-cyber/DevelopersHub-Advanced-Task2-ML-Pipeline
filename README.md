# End-to-End Machine Learning Pipeline for Customer Churn Prediction

## Project Overview

This project was completed as part of the DevelopersHub Corporation AI/ML Advanced Internship.

The objective is to build a reusable machine learning pipeline that predicts customer churn using the IBM Telco Customer Churn dataset.

## Dataset

IBM Telco Customer Churn Dataset

## Machine Learning Models

- Logistic Regression
- Random Forest Classifier

## Pipeline Components

- Missing Value Imputation
- Standard Scaling
- One-Hot Encoding
- ColumnTransformer
- Scikit-learn Pipeline API

## Hyperparameter Optimization

GridSearchCV was used to optimize the Random Forest model.

Best Parameters:

- Max Depth = 10
- Min Samples Split = 5
- Number of Trees = 200

## Model Performance

| Metric | Value |
|--------|-------|
| Accuracy | 0.7999 |
| Precision | 0.6565 |
| Recall | 0.5160 |
| F1 Score | 0.5778 |

## Files Included

- Customer_Churn_ML_Pipeline.ipynb
- churn_pipeline.pkl
- README.md
- requirements.txt

Screenshots:

- Dataset Preview
- Missing Values
- Model Results
- Confusion Matrix
- Feature Importance
- Project Summary

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- Joblib
- Matplotlib
