#  Medical-Insurance-Cost-Prediction
This project implements a machine learning model to predict medical insurance costs based on various factors such as age, sex, BMI, smoking habits, region, and number of children. The dataset used for this project contains 3630 instances with 6 features.


Dataset:
The dataset used is sourced from Google Drive (link provided in the README) and contains the following columns:

Age
Sex
BMI (Body Mass Index)
Smoker (Yes/No)
Region
Number of Children
Charges (Insurance cost)
Data Preprocessing
The dataset is preprocessed to handle categorical features and prepare the data for modeling:

Encoding categorical variables (Sex, Smoker, Region)
Splitting the data into training and testing sets (80% training, 20% testing)
Model Training
The machine learning model used for this project is Linear Regression from scikit-learn.

Model Evaluation
The model is evaluated using R-squared score on both training and testing datasets to assess its performance.

Predictive System
A predictive system is implemented to predict insurance costs based on user-provided input data.

Requirements
Python 3.x
Libraries: numpy, pandas, matplotlib, seaborn, scikit-learn
License
This project is licensed under the MIT License - see the LICENSE file for details.
