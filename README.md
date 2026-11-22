# Customer Churn Prediction

## Project Overview

This project focuses on analyzing customer churn using data analysis, statistical analysis, and machine learning techniques.

The goal is to understand customer behavior, identify factors associated with customer churn, build machine learning models to predict churn, and segment customers based on their estimated churn risk.

The project also includes Power BI dashboard development to present the analysis and model results in an interactive business intelligence format.

## Project Structure

Customer_Churn_Prediction/

├── data/
├── notebooks/
│   └── data_understanding.ipynb
├── powerbi/
├── README.md
├── requirements.txt
└── .gitignore

## Dataset

The dataset contains customer-related information used to analyze churn behavior.

The analysis includes customer demographics, service information, contract details, payment methods, tenure, and billing information.

The final customer-level dataset also includes estimated churn probability and customer risk level.

## Project Workflow

- Data understanding and inspection
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Statistical analysis
- Feature engineering
- Machine learning model development
- Model evaluation and comparison
- Customer churn probability prediction
- Customer risk segmentation
- Power BI dashboard development

## Machine Learning Models

Three classification models were developed and evaluated:

- Logistic Regression
- Random Forest
- XGBoost

Logistic Regression was selected as the final model based on the overall evaluation results, including ROC-AUC, precision, recall, and F1-score.

## Customer Risk Segmentation

The final model was used to estimate individual customer churn probabilities.

Customers were then categorized into:

- Low Risk
- Medium Risk
- High Risk

This segmentation can help businesses prioritize customer retention efforts.

## Power BI Dashboard

The project includes Power BI dashboard development based on the final customer-level dataset and machine learning results.

The dashboard is designed to present:

- Overall churn metrics
- Churn patterns across customer segments
- Customer churn probability
- Customer risk levels
- Model performance comparison

The Power BI-ready datasets are exported from the Jupyter Notebook as CSV files.

## Tools and Technologies

- Python
- JupyterLab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Scikit-learn
- XGBoost
- Power BI

## Future Steps

- Develop additional customer retention strategies based on risk segments
- Deploy the churn prediction model as an interactive application
- Integrate the model with new customer data
- Monitor model performance over time
- Explore automated churn monitoring and alerts

## Author

Customer Churn Analysis Project