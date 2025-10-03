# Employee Turnover Analysis and Retention Strategies
Welcome to the Employee Turnover Analysis and Retention Strategies repository! This project leverages machine learning to analyze, predict, and understand employee turnover, as well as to recommend targeted retention strategies for organizations.
Overview
Portobello Tech, an app innovator, sought an intelligent approach to foresee employee turnover and retain its top talent. This project analyzes HR data to identify patterns related to turnover and provides actionable strategies for employee retention, using a combination of data analysis, machine learning, and cluster-based employee segmentation.

# Features

Data Quality Checks: Assesses and cleans datasets for missing values and proper data types.
Exploratory Data Analysis (EDA): Examines numerical and categorical drivers of turnover, including satisfaction, performance, and project workload.
Clustering & Pattern Discovery: Uses unsupervised learning to cluster employees based on their satisfaction and performance.
Predictive Modeling: Implements and compares Logistic Regression, Random Forest, and Gradient Boosting classifiers to predict turnover.
Risk Zoning: Categorizes employees into four risk zones (Safe, Low, Moderate, High) for tailored retention strategies.
Retention Strategy Generator: Recommends zone-specific HR actions based on model predictions.


# Data

Features Used: Number of projects, average monthly hours, tenure, promotion history, salary, satisfaction level, and more.
Data Handling: Categorical variables (e.g., department, salary) are converted to dummy variables for modeling.
Class Imbalance: Addresses minority classes (those leaving) using SMOTE (Synthetic Minority Over-sampling Technique).


# Analysis Highlights

Correlation Analysis: Identifies links between workload, satisfaction, and turnover. Lower satisfaction strongly correlates with higher turnover.
Project Count Analysis: Employees with 2 or ≥5 projects are most at risk—either underutilized or overburdened.
Cluster Insight: Reveals that high performance does not always guarantee retention if satisfaction is low.
Model Results:

Random Forest achieves the best recall (0.98), outperforming Logistic Regression (0.75) and Gradient Boosting (0.93).
ROC/AUC and confusion matrices validate model effectiveness.




# Retention Strategies
For each predicted risk zone, this project recommends:

Safe Zone: Continue standard engagement.
Low Risk: Closely monitor satisfaction and provide feedback.
Moderate Risk: Offer tailored retention programs and career development.
High Risk: Conduct stay interviews; address urgent concerns.
