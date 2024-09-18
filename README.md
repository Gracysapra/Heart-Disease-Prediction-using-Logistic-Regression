# Heart-Disease-Prediction-using-Logistic-Regression
This project aims to predict the likelihood of heart disease using Logistic Regression. The dataset contains medical information, including attributes such as age, cholesterol levels, blood pressure, and other factors. The goal is to predict whether or not a patient has heart disease (binary classification).

## Dataset Information:
The dataset consists of 1025 entries and 14 columns, with features such as:

age: Age of the patient
sex: Gender of the patient (1 = male, 0 = female)
cp: Chest pain type (categorized from 0 to 3)
trestbps: Resting blood pressure (in mm Hg)
chol: Serum cholesterol (in mg/dl)
fbs: Fasting blood sugar (> 120 mg/dl)
restecg: Resting electrocardiographic results
thalach: Maximum heart rate achieved
exang: Exercise-induced angina (1 = yes, 0 = no)
oldpeak: ST depression induced by exercise
slope: Slope of the peak exercise ST segment
ca: Number of major vessels colored by fluoroscopy (0–4)
thal: Thalassemia (3 = normal, 6 = fixed defect, 7 = reversible defect)
target: Target variable (1 = heart disease, 0 = no heart disease)
## Key Steps in the Project:
### Data Preprocessing:

The dataset is cleaned and split into training and testing sets using train_test_split from scikit-learn.
Features are selected based on medical significance, including age, cholesterol levels, and maximum heart rate.
### Model Training:

A Logistic Regression model is trained to predict the probability of heart disease.
The model is fitted on the training data and tested on unseen data to evaluate its performance.
### Model Evaluation:

The performance of the model is evaluated using metrics such as accuracy, confusion matrix, and classification report.
These metrics help determine how well the model predicts heart disease.
### Gradio User Interface:

An interactive interface using Gradio allows users to input relevant medical data (e.g., age, cholesterol levels, resting blood pressure).
The interface provides real-time predictions on whether the patient is likely to have heart disease.
## Features:
Logistic Regression: Used for binary classification to predict whether a patient has heart disease.
Performance Metrics: Includes accuracy, confusion matrix, and classification report to evaluate the model's performance.
Interactive Interface: The Gradio interface enables users to input medical attributes and predict heart disease risk in real time.

This project provides a comprehensive solution for heart disease prediction using logistic regression and a user-friendly interface for real-time prediction.
