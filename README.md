# Diabetes Prediction Using Logistic Regression

## Overview

This project uses **Logistic Regression** to predict whether a patient is diabetic or not based on medical diagnostic measurements. The goal is to build a classification model that can assist in early diabetes detection using patient health data.

---

## Problem Statement

In this project, a machine learning model is built to predict whether a patient has diabetes using features such as glucose level, BMI, age, insulin, and other health-related factors.

Target Variable:

* **0 → Non-Diabetic**
* **1 → Diabetic**

---

## Dataset Information

The dataset contains medical information of patients with the following features:

* Pregnancies
* Glucose
* BloodPressure
* SkinThickness
* Insulin
* BMI
* DiabetesPedigreeFunction
* Age

Target:

* Outcome

Dataset size:

* 768 rows
* 9 columns

---

## Project Workflow

### 1. Data Collection

Loaded the diabetes dataset using Pandas.

### 2. Exploratory Data Analysis (EDA)

Performed analysis using:

* Correlation Heatmap
* Boxplots
* Countplots
* Barplots

Key insights were extracted from:

* Glucose vs Outcome
* Age vs Outcome
* BMI vs Outcome

### 3. Data Preprocessing

* Checked for missing values
* Split features and target
* Applied feature scaling using StandardScaler

### 4. Model Training

Used **Logistic Regression** for binary classification.

### 5. Model Evaluation

Evaluated performance using:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

### 6. Feature Importance Analysis

Analyzed Logistic Regression coefficients to understand which features influence diabetes prediction the most.

---

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

---

## Machine Learning Algorithm

* Logistic Regression
  
---

## Evaluation Metrics

The model performance was measured using:

* Accuracy Score
* Precision Score
* Recall Score
* F1 Score
* Confusion Matrix

These metrics help evaluate classification performance and prediction reliability.

---

## Results

The model successfully predicts diabetes based on patient health data.

Important features influencing prediction include:

* Glucose
* BMI
* Age
* Diabetes Pedigree Function

---

## Project Structure

Diabetes-Prediction-Using-Logistic-Regression/

* dataset/
* notebook/
* images/
* README.md

---

## Future Improvements

* Hyperparameter tuning
* Compare with other classification algorithms
* Deploy using Streamlit or Flask
* Improve model performance using advanced techniques

---

## Conclusion

This project demonstrates how Logistic Regression can be used for healthcare prediction problems. It provides valuable insights into diabetes risk factors and helps in understanding binary classification workflows in machine learning.

---
## Author

ISHANI KABRA

---
