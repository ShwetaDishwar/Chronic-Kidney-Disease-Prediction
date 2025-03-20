# Chronic Kidney Disease Prediction Model

This project involves building a machine learning model to predict Chronic Kidney Disease (CKD) using patient data. The goal is to clean and preprocess the data, build predictive models, and evaluate their performance.

Project Overview
Dataset: Kidney disease dataset containing 400 patient records and 25 features.
Goal: Predict the likelihood of CKD based on patient attributes like age, blood pressure, specific gravity, red blood cell count, and other health indicators.


Key Steps

Data Cleaning
- Removed irrelevant columns (like ID).
- Converted categorical values to lowercase and handled inconsistencies.
- Filled missing numeric values with median and categorical values with mode.

Feature Encoding
- Applied label encoding to categorical columns.

Model Training and Evaluation
- Split the dataset into training (80%) and testing (20%).
- Trained Logistic Regression and Random Forest models.
- Evaluated using accuracy, precision, recall, and classification reports.

Model Performance
- Logistic Regression: 92.5% accuracy
- Random Forest: 100% accuracy

Model Insights
- Explored feature importance using Random Forest.
- Created confusion matrix and ROC curve to visualize model performance.

Future Enhancements
- Adding more patient data to improve generalization.
-Testing additional machine learning algorithms for better comparison.
-Fine-tuning hyperparameters to enhance model performance.

Skills Used
Python, Pandas, Scikit-Learn, Matplotlib, Seaborn, Data Preprocessing, Machine Learning
