# Customer Churn Prediction (Consulting Case Study)
Customer churn analysis using Python and machine learning

## Business Problem
Customer churn is a critical challenge for subscription-based businesses. Retaining existing customers is more cost-effective than acquiring new ones. This project aims to identify customers who are most likely to churn and provide actionable insights to reduce churn.

## Business Question
Which customers are most likely to churn, and what actions should the business take to reduce churn?

## Business Objectives
- Predict customer churn (Yes / No)
- Identify key drivers of churn
- Provide data-driven, actionable recommendations

## Stakeholders
- Marketing Team
- Customer Retention Team
- Executive Leadership

## Tools & Technologies
- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- Jupyter Notebook
- 
## Project Structure & Notebooks

This project is organized into multiple Jupyter notebooks to clearly separate each stage of the data science workflow.

### Notebook 1: 01_data_exploration_eda.ipynb
- Loaded and inspected the raw customer churn dataset
- Performed exploratory data analysis (EDA) to understand customer behavior
- Analyzed churn distribution across key variables such as contract type, and monthly charges
- Identified early churn patterns and data quality issues to guide feature engineering

### Notebook 2: 02_data_cleaning_feature_engineering.ipynb
- Cleaned and prepared the dataset for modeling
- Handled data type issues and missing values
- Encoded categorical variables and engineered churn-related features
- Split the data into training and testing sets

### Notebook 3: 03_modeling_evaluation.ipynb
- Built baseline and advanced machine learning models (Logistic Regression, Random Forest)
- Evaluated models using accuracy, recall, precision, F1-score, and ROC-AUC
- Compared model performance with a focus on recall for churners (class = 1)

### Notebook 4: 04_explainable_ai.ipynb
- Applied SHAP for model explainability and feature impact analysis
- Generated customer-level churn probabilities and risk segments
- Translated model outputs into actionable business recommendations

