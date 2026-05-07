# Lloyds Banking Group — Customer Churn Prediction
**Forage Data Science Virtual Experience Programme**

## Project Overview
Predicting customer churn for Lloyds Banking Group using machine learning.

## Task 1 — EDA & Preprocessing
- Explored 5 data sources (1,000 customers)
- Engineered features: DaysSinceLogin, ComplaintCount, TotalSpent
- Cleaned, encoded, and standardised data (25 features, 0 missing values)
- Churn rate: 20.4%

## Task 2 — Predictive Model
- Algorithm: Logistic Regression (balanced class weights, L2 regularisation)
- Cross-validation: 5-fold stratified (ROC-AUC = 0.536)
- Recall: 47.6% (identifies at-risk customers for retention)

## Files
| File | Description |
|---|---|
| `Customer-Churn-Prediction.docx` | Task 1 — EDA & preprocessing report |
| `Task2_Churn_Model_Report.docx` | Task 2 — ML model report |
| `Lyods.csv` | Cleaned, model-ready dataset |
| `Customer_Churn_Data_Large.xlsx` | Raw data source |

## Tools Used
Python, pandas, scikit-learn, matplotlib, seaborn, Power BI
