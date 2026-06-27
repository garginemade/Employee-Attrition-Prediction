# Employee Attrition Prediction using Machine Learning

## Project Overview
This project predicts whether an employee is likely to leave the company using machine learning. It includes data preprocessing, exploratory data analysis (EDA), model building, evaluation, and business recommendations for HR.

## Dataset
IBM HR Analytics Employee Attrition Dataset

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow
- Data Loading & Exploration
- Data Cleaning & Preprocessing
- Exploratory Data Analysis
- Model Building
- Model Evaluation
- Feature Importance
- HR Recommendations

## Machine Learning Models
- Logistic Regression
- Random Forest Classifier
- Gradient Boosting Classifier

## Results
Among the three models, Logistic Regression performed the best based on overall evaluation metrics. The analysis showed that overtime, monthly income, and years at the company were among the most important factors influencing employee attrition.

## Project Structure

```text
Employee-Attrition-Prediction/
│
├── analysis.ipynb
├── HR_Attrition.csv
├── README.md
├── summary.pdf
│
└── charts/
    ├── attrition_rate_department.png
    ├── attrition_rate_job_role.png
    ├── attrition_rate_department_job_role.png
    ├── monthly_income_boxplot.png
    ├── attrition_vs_monthly_income.png
    ├── attrition_vs_work_life_balance.png
    ├── attrition_vs_years_at_company.png
    ├── confusion_matrix.png
    ├── top_10_feature_importance.png
    └── roc_curve_comparison.png
```
