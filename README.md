# **Project Overview**

This project focuses on classifying customer loan eligibility by analyzing the credit strategy of a masked dataset of 51,336 customers with 79 features.
The goal is to identify high-risk and low-risk customers, ensuring better decision-making in lending strategies.

## **Table of Contents**

1. Dataset & Objective

2. Key Techniques & Workflow

3. Modelling Approaches

4. Results

## **Dataset & Objective**

* Objective: Predict which customers are eligible for loans.
* Data: Masked dataset containing 51,336 entries, each with 79 features including demographic, financial, and behavioral metrics.

## **Key Techniques & Workflow**

* Feature Engineering: Created new variables and refined existing ones.

### Hypothesis Testing:

* Chi-Square tests for categorical relevance
* ANOVA to compare means across groups
* Sequential VIF to detect multicollinearity
* Class Imbalance Handling: Applied SMOTE to balance classes.
* Distribution Analysis: Used Kolmogorov–Smirnov test to compare feature distributions.

## **Modelling Approaches**

* Baseline: Logistic Regression (One-vs-Rest).
* Ensembles: Random Forest, XGBoost.
* Optimization: Applied Optuna for hyperparameter tuning, boosting model performance.

## **Results**

Achieved 80% accuracy with XGBoost after tuning.
Improved fairness and stability of the model through advanced statistical tests and balancing techniques.
