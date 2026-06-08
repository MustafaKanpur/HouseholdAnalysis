Household Expenditure Analysis
A machine learning project analyzing household demographic and spending data to uncover spending patterns and predict expenditure. Built collaboratively by a team of 4.
Overview
This project performs end-to-end data analysis on merged demographic and household spending datasets. The pipeline covers data cleaning through to model interpretation, applying both unsupervised and supervised learning techniques to understand what drives household spending behavior.
Features

Data cleaning and preprocessing — outlier treatment, missing value resolution, and feature engineering across hundreds of variables
Unsupervised learning — KMeans clustering with PCA for dimensionality reduction, evaluated using silhouette scores and the elbow method
Supervised learning — XGBoost regression model tuned with GridSearchCV and K-Fold cross-validation
Model evaluation — MSE, R², and bootstrap confidence intervals for robust performance assessment
Model interpretability — SHAP values with dependence plots and ranked feature importance summaries to identify key spending drivers

Tech Stack
Python, Pandas, NumPy, Scikit-learn, XGBoost, SHAP, Matplotlib
Team
Built by a team of 4 as part of a data science course project at the University of Western Ontario.
