# Customer Churn Analysis

## Project Overview

Customer Churn Analysis is a data analytics and machine learning project that analyzes customer behavior and identifies factors that contribute to customer churn.

The project uses the IBM Telco Customer Churn dataset and applies Python-based data analysis, machine learning models, and Tableau visualization.

## Objectives

- Analyze customer churn patterns
- Identify important factors affecting churn
- Perform data cleaning and exploratory data analysis
- Build machine learning models to predict churn
- Compare Logistic Regression and Random Forest
- Create an interactive Tableau dashboard

## Dataset

- Records: 7,043 customers
- Features: 21 attributes
- Target: Customer Churn

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- Tableau Public

## Analysis Performed

- Data cleaning and preprocessing
- Exploratory Data Analysis
- Churn analysis by contract
- Internet service analysis
- Payment method analysis
- Tenure analysis
- Monthly charges analysis
- Tech support analysis
- Online security analysis
- Correlation analysis
- Customer churn probability
- Risk analysis
- Feature importance

## Machine Learning Models

### Logistic Regression

- Accuracy: 79.91%
- Precision: 65.22%
- Recall: 52.14%
- F1 Score: 57.95%

### Random Forest

- Accuracy: 78.85%
- Precision: 62.93%
- Recall: 49.47%
- F1 Score: 55.39%

## Model Comparison

| Model | Accuracy | Precision | Recall | F1 Score |
|---|---:|---:|---:|---:|
| Logistic Regression | 79.91% | 65.22% | 52.14% | 57.95% |
| Random Forest | 78.85% | 62.93% | 49.47% | 55.39% |

## Key Findings

- Month-to-month contract customers have higher churn.
- Higher monthly charges are associated with higher churn.
- Fiber optic customers show relatively higher churn.
- Customers without online security or tech support are more likely to churn.
- Longer-tenure customers generally have lower churn.
- Logistic Regression performed slightly better than Random Forest.

## Tableau Dashboard

![Customer Churn Dashboard](images/dashboard.png)

## Project Structure

```text
Customer-Churn-Analysis/
├── data/
│   ├── raw/
│   │   └── WA_Fn-UseC_-Telco-Customer-Churn.csv
│   └── processed/
│       ├── cleaned_customer_churn.csv
│       └── model_performance.csv
├── notebooks/
│   └── 01_customer_churn_analysis.ipynb
├── dashboard/
├── images/
│   └── dashboard.png
├── README.md
└── requirements.txt
