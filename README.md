# Ensemble-Technique-Automated-Project
A program that takes in file location and target column and goes through multiple ML algorithms such as
Logistic Regression
SVM
Random Forest
CatBoost 
And gives you the best performing model based on your performance priority and even saves the trained model as a pickle file.

Logistics Regression uses GridSearchCV to hypertune parameters.
Parameters used:

solver: ['newton-cg', 'lbfgs', 'liblinear', 'sag', 'saga']

C: [10, 1.0, 0.1]
