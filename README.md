# Project Summary
## Employee Turnover Prediction Using Machine Learning

This project develops an end-to-end machine learning pipeline to predict employee turnover and identify key factors influencing attrition.

### Objective :-
  - To predict whether an employee is likely to leave the organization and provide actionable insights for HR teams to improve employee retention.

### Dataset
  - 1,350 employee records
  - 15 workforce-related features
  - Binary target variable: Employee Turnover (Yes/No)

### Workflow
  - Data loading and quality assessment
  - Exploratory Data Analysis (EDA)
  - Correlation and multicollinearity analysis
  - Feature engineering validation
  - Stratified train-test splitting
  - Model training and comparison
  - Performance evaluation
  - Business interpretation and HR recommendations

### Models Evaluated
  - Logistic Regression (Baseline)
  - Logistic Regression with L1 Regularization
  - Logistic Regression with L2 Regularization
  - Random Forest Classifier
  - XGBoost Classifier

### Evaluation Metrics
  - Accuracy
  - Precision
  - Recall
  - F1 Score
  - ROC-AUC
  - Cross-Validation Performance
  - Confusion Matrix Analysis

## Key Insights
  - Job Satisfaction is one of the strongest predictors of employee turnover.
  - Work-Life Balance and Distance From Home significantly influence attrition risk.
  - Compensation-related features contribute meaningfully to prediction performance.
  - Ensemble models outperform traditional logistic regression approaches.

## Business Impact
  - The model can be used as an early-warning system to identify high-risk employees, enabling HR teams to implement proactive retention strategies and reduce turnover costs.

## Outcome
- Random Forest/XGBoost achieved the strongest predictive performance and demonstrated the ability to effectively identify employees at risk of leaving the organization.
