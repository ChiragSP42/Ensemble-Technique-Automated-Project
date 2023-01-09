# Ensemble-Technique-Automated-Project
This project is based on the case study of a telecommunication company, which is facing a customer churn issue. The project aims at understanding the pattern of the data and predicting customers who are going to churn based on multiple variables to help the company in retaining their existing customers. 
The project was accomplished by building a machine learning workflow that will run autonomously with the CSV file and return the best-performing model.

The project takes in file location and target column and goes through multiple ML algorithms such as;
1. Logistic Regression
2. SVM
3. Random Forest
4. CatBoost 
And gives you the best performing model based on your performance priority and even saves the trained model as a pickle file.

Logistics Regression uses GridSearchCV to hypertune parameters.
Parameters used:

solver: ['newton-cg', 'lbfgs', 'liblinear', 'sag', 'saga']

C: [10, 1.0, 0.1]
