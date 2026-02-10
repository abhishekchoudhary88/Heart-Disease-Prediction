
❤️ Heart Disease Prediction using Machine Learning
📌 Project Overview

This project aims to predict whether a person is likely to have heart disease based on various medical attributes using Machine Learning.
Heart disease is one of the leading causes of death worldwide, and early prediction can help in timely medical intervention.

In this project, we analyze patient health data, perform data preprocessing, apply machine learning algorithms, and build a predictive model that classifies whether a patient has heart disease or not.

🎯 Objective

To analyze medical data related to heart disease

To understand relationships between health parameters

To build a binary classification model

To predict presence or absence of heart disease

To gain hands-on experience in end-to-end ML workflow

🧠 Technologies & Tools Used

Python

Pandas – data manipulation

NumPy – numerical computation

Matplotlib & Seaborn – data visualization

Scikit-learn – ML models & evaluation

📂 Dataset Description

The dataset contains patient medical records with multiple health indicators.

Common Features:

age – Age of patient

sex – Gender (1 = male, 0 = female)

cp – Chest pain type

trestbps – Resting blood pressure

chol – Serum cholesterol

fbs – Fasting blood sugar

restecg – Resting ECG results

thalach – Maximum heart rate achieved

exang – Exercise induced angina

oldpeak – ST depression

target – 0 = No Heart Disease, 1 = Heart Disease

🔄 Project Workflow (Step-by-Step)
Step 1: Import Required Libraries

All necessary libraries are imported for:

Data handling

Visualization

Machine learning modeling

Step 2: Load the Dataset

The dataset is loaded using pandas and initial exploration is done:

Checking dataset shape

Viewing sample rows

Understanding feature types

Step 3: Exploratory Data Analysis (EDA)

EDA is performed to understand the data:

Distribution of age and gender

Correlation between features

Relationship between target and medical attributes

Visualization using bar plots and heatmaps

This step helps in identifying important features affecting heart disease.

Step 4: Data Preprocessing

Handle missing values (if any)

Separate features (X) and target variable (y)

Normalize or scale data if required

Prepare data for machine learning models

Step 5: Train-Test Split

The dataset is divided into:

Training data – to train the model

Testing data – to evaluate performance

This ensures unbiased evaluation.

Step 6: Model Training

Machine Learning classification algorithms are used to train the model.
The model learns patterns between medical features and heart disease outcomes.

Step 7: Model Evaluation

The trained model is evaluated using:

Accuracy score

Confusion matrix

Classification report

This helps measure how well the model predicts heart disease.

Step 8: Prediction on New Data

The model can predict heart disease for new patient data by:

Taking input medical values

Applying the trained model

Returning prediction (disease / no disease)
