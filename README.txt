Adult Census Income Classification Project

Project Overview
This project applies machine learning techniques to predict whether an individual earns more than $50,000 per year using the Adult Census Income dataset from the UCI Machine Learning Repository. The project demonstrates a complete data science workflow including exploratory data analysis, data preprocessing, model training, and evaluation.

Dataset
Source: UCI Machine Learning Repository – Adult Census Income Dataset
Observations: Approximately 48,842
Target Variable: Income (<=50K vs. >50K)
Features: Demographic and employment-related variables such as age, education, occupation, hours per week, and capital gain/loss.

Methods Used
- Exploratory Data Analysis (EDA) with multiple visualizations
- Data cleaning and preprocessing
- Train/test split (80/20, stratified)
- Feature scaling for applicable models

Models Trained
- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boosting
- K-Nearest Neighbors (KNN)

Evaluation
Models were evaluated using accuracy, ROC-AUC, confusion matrices, ROC curves, and feature importance analysis. Ensemble models (Random Forest and Gradient Boosting) achieved the best overall performance.

Future Improvements
Potential future work includes hyperparameter tuning, cross-validation, alternative encoding strategies, handling class imbalance, and deploying the model as an application.
