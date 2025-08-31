**Project Overview**

This project focuses on classifying customer loan eligibility by analyzing the credit strategy of a masked dataset of 51,336 customers with 79 features.
The goal is to identify high-risk and low-risk customers, ensuring better decision-making in lending strategies.

**Key Highlights**

Feature Engineering (FE) and preprocessing to prepare the dataset.

**Statistical analysis & Hypothesis Testing:**

Chi-Square Test, 
ANOVA,
Sequential VIF (Variance Inflation Factor).

Data balancing: 
SMOTE applied to handle class imbalance,
Distribution comparison using the Kolmogorov–Smirnov test.

**Modeling Approaches:**

Logistic Regression (One-vs-Rest),
Random Forest,
XGBoost (with Optuna hyperparameter tuning),

Performance Achieved:

Best accuracy of 80% using XGBoost.

**Tech Stack**

Python,
Pandas, NumPy,
Scikit-learn,
XGBoost,
Optuna (Hyperparameter Optimization),
Imbalanced-learn (SMOTE),
Matplotlib, Seaborn (Visualization),

**Results**

Achieved 80% accuracy with XGBoost after tuning.
Improved fairness and stability of the model through advanced statistical tests and balancing techniques.
