Diabetes Risk Prediction – Nova Health Center

Project Overview
Nova Health Center is a multi-specialty clinic serving over 20,000 patients annually across both urban and rural areas.

In recent years, the prevalence of diabetes among patients has been rising steadily, now affecting 1 in 10 adults,consistent with global statistics (WHO, 2023).

A growing challenge is late diagnosis:

Many patients are only identified after developing severe complications, including:

-Neuropathy (nerve damage)

-Kidney failure

-Cardiovascular disease

Physicians have emphasized the need for a data-driven early detection system to:

-Identify high-risk individuals early

-Enable personalized interventions

-Reduce missed diagnoses during routine checkups

Project Objectives

The aim of this project is to leverage patient health records to develop a machine learning model that predicts an individual’s risk of developing diabetes.

The solution will:

Analyze patient data to identify patterns linked to diabetes risk.

Predict high risk individuals before symptoms escalate.

Support physicians with actionable, interpretable insights.

Enable personalized lifestyle and treatment recommendations.


Dataset

The dataset provided includes anonymized patient records with the following features:

Feature	Description

Age---Patient age (years)

BMI---Body Mass Index

BloodPressure---Resting blood pressure (mm Hg)

Glucose	Blood---glucose level (mg/dL)

Insulin	Blood---insulin level (μU/mL)

ExerciseDays---Days of exercise per week

FamilyHistory---Binary indicator of diabetes in immediate family

DiabetesRiskScore---Target variable indicating diabetes risk

Note: All data has been anonymized and is used in compliance with data protection regulations.

Methodology

-Data Cleaning & Preprocessing

-Handling missing values and outliers

-Encoding categorical variables

-Normalizing numerical features

-Exploratory Data Analysis (EDA)

-Understanding feature distributions

-Identifying correlations between predictors and target

-Visualizing trends and patterns

Feature Engineering

Creating new features (e.g., BMI categories)

Selecting the most predictive variables

Model Development

Testing multiple algorithms: Logistic Regression, Random Forest, XGBoost

Hyperparameter tuning for optimal performance

Model Evaluation

Using metrics such as ROC-AUC, Precision, Recall, and F1-score

Cross-validation to ensure robustness

Interpretability

Applying SHAP values to highlight key risk factors

Presenting feature importance to physicians

Expected Outcomes:

Risk Prediction Tool – ML model to flag high-risk patients during checkups

Explainable Results – Clearly showing factors influencing each patient’s score

Clinical Integration – Framework for embedding predictions into routine workflows

Impact

Early detection can:

-Reduce the rate of severe diabetes complications

-Support targeted preventive care

-Enable physicians to focus resources where they are most needed

-Improve long-term health outcomes in both rural and urban communities

