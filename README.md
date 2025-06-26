# AI-Development-Workflow-Assignment
Project Overview
This project explores the development of AI models to address two real-world problems:

Predicting Employee Attrition in a mid-sized tech company.

Predicting Hospital Readmissions within 30 days of discharge.

Part 1: Employee Attrition Prediction
Objective
Identify employees at risk of leaving.

Analyze contributing factors like satisfaction and workload.

Help HR proactively improve retention.

Data Sources
Human Resource Information System (HRS)

Employee Engagement Surveys

Preprocessing
Handle missing data using imputation.

Encode categorical variables.

Normalize features.

Model
Random Forest Classifier

Evaluation using F1 Score and AUC-ROC.

Monitor for concept drift and scale using cloud platforms if needed.

Part 2: Hospital Readmission Prediction
Objective
Predict 30-day readmission likelihood.

Identify risk factors and support post-discharge care.

Data Sources
EHRs, demographic, insurance, and feedback data.

Preprocessing
Clean and engineer features.

Use NLP for text data.

Address class imbalance with SMOTE.

Model
XGBoost with SHAP for interpretability.

Deployed via secure cloud with EHR integration.

Part 3: Ethical and Practical Concerns
Address data bias using stratified sampling.

Balance interpretability vs. accuracy.

Choose models suited to available computing resources.

Part 4: Workflow Challenges
Most challenging step: Data preprocessing and feature engineering.

Suggested improvements include greater domain expert collaboration and use of NLP and monitoring tools.
