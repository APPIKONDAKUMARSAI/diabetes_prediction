# diabetes_prediction
1. Diabetes Prediction Web Application (Flask + ML)

A Machine Learning web application built using Logistic Regression and deployed using Flask.
The system predicts whether a person is diabetic based on medical input parameters.

2. Project Overview

This project uses the PIMA Indians Diabetes Dataset to train a classification model that predicts diabetes using patient medical attributes.

The trained model is deployed as a web application using Flask, allowing users to enter patient details and receive instant predictions.

3. Machine Learning Details
🔹 Algorithm Used

Logistic Regression

🔹 Data Preprocessing

Train-Test Split (80-20)

Feature Scaling using StandardScaler

🔹 Model Performance

Training Accuracy: 79%

Testing Accuracy: 71%

4. Features Used for Prediction

Pregnancies

Glucose Level

Blood Pressure

Skin Thickness

Insulin

BMI

Diabetes Pedigree Function

Age

5. Project Architecture

User enters medical details in the web form.

Flask receives the input via POST request.

Input data is scaled using saved StandardScaler.

Logistic Regression model makes prediction.

Result is rendered dynamically using Jinja2 templates.

source : https://www.kaggle.com/datasets/saurabh00007/diabetescsv?resource=download

sample view: 
