# Customer Churn Analysis

## Project Overview
Analysis of customer churn using the IBM Telco Customer Churn dataset.

## Objectives
- Identify factors affecting customer churn
- Analyze customer behavior
- Predict customers likely to churn
- Compare Logistic Regression and Random Forest models
- Build an interactive Tableau dashboard

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Tableau Public
- Jupyter Notebook

## Dataset
IBM Telco Customer Churn dataset containing 7,043 customer records and 21 attributes.

## Analysis Performed
- Data cleaning and preprocessing
- Exploratory Data Analysis
- Churn analysis by contract, internet service and payment method
- Tenure and monthly charges analysis
- Correlation analysis
- Logistic Regression
- Random Forest
- Model evaluation
- Customer churn risk analysis

## Model Performance

| Model | Accuracy | Precision | Recall | F1 Score |
|---|---:|---:|---:|---:|
| Logistic Regression | 79.91% | 65.22% | 52.14% | 57.95% |
| Random Forest | 78.85% | 62.93% | 49.47% | 55.39% |

## Key Findings
- Contract type has a strong relationship with churn.
- Customers with higher monthly charges show greater churn tendency.
- Fiber optic customers show higher churn compared with other internet-service groups.
- Logistic Regression performed slightly better than Random Forest.

## Dashboard
![Customer Churn Dashboard](images/dashboard.png)

## Project Structure
Customer Churn Analysis/
- data/
- notebooks/
- dashboard/
- images/
- README.md
- requirements.txt

## How to Run
1. Install the required Python libraries.
2. Open the Jupyter Notebook.
3. Run the cells in order.
4. Open the Tableau workbook to view the dashboard.
