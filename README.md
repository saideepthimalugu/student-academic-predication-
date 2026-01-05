**Title: Student Performance Prediction Using Machine Learning
 Project Overview**

This project uses machine learning techniques to predict student final grades (G3) based on 
socio-demographic, behavioural, and academic factors. The goal is to analyse which factors 
most influence student performance and to build accurate regression models that can predict final outcomes
**Aim of the Project**
To identify key factors influencing student academic performance
To build and compare machine learning regression models
To accurately predict final student grades (G3)
To demonstrate the use of machine learning in educational data analysis
**Dataset Used**
Dataset Name: Student Performance Dataset
Source: UCI Machine Learning Repository
Original Collection: Two public secondary schools in Portugal
Subjects: Mathematics and Portuguese
Records: 1,044 students (combined dataset)
Features: 34 attributes (demographic, behavioural, academic)
The dataset is anonymised and collected using school reports and questionnaires.
**input Format**
CSV files containing student data
Features include:
Demographics (age, gender)
Family background (parental education, support)
Behaviour (study time, absences, alcohol consumption)
Academic history (G1, G2)
**Output Format**
Predicted final grade (G3) for each student
Model evaluation metrics:
Mean Absolute Error (MAE)
Root Mean Squared Error (RMSE)
R² Score
Visual outputs:
Feature importance plots
Actual vs predicted grade plots
Model comparison charts
**Models Implemented**
Random Forest Regressor
Gradient Boosting Regressor
Support Vector Regression (SVR)
Hyperparameter tuning is performed using RandomizedSearchCV
**Technologies Used**
Python
Pandas, NumPy
Scikit-learn
Matplotlib, Seaborn
Jupyter Notebook
