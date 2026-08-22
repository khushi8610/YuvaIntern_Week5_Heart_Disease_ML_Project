# YuvaIntern_Week5_Heart_Disease_ML_Project
# Yuva Intern Week 5 – Comprehensive Data Science Project Reporting and Strategic Recommendations

## 📌 Project Overview

This project is developed as part of the **Yuva Intern Week 4: Machine Learning Model Development and Evaluation** task.

The objective of this project is to develop and evaluate machine learning classification models that can predict whether a patient is likely to have heart disease based on various medical attributes.

The project demonstrates the complete machine learning workflow, starting from data preparation and exploratory data analysis to model training, evaluation, visualization, and comparison.

---

## 🎯 Objectives

The main objectives of this project are:

- Understand and preprocess a real-world healthcare dataset.
- Perform exploratory data analysis.
- Prepare features and target variables.
- Split the dataset into training and testing sets.
- Apply feature scaling.
- Train machine learning classification models.
- Evaluate model performance using multiple metrics.
- Visualize model performance using a confusion matrix and ROC curve.
- Compare different machine learning models.
- Analyze limitations and possible improvements.

---

## 📊 Dataset

The project uses a **Heart Disease Dataset obtained from Kaggle**.

### Dataset Details

| Property | Details |
|---|---|
| Dataset Type | Binary Classification |
| Number of Records | 1888 |
| Number of Features | 13 |
| Target Variable | `target` |
| Class 0 | No Heart Disease |
| Class 1 | Presence of Heart Disease |

### Features

The dataset contains medical attributes such as:

- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Resting ECG
- Maximum Heart Rate
- Exercise-Induced Angina
- ST Depression
- Slope
- Number of Major Vessels
- Thalassemia

---

## 🧠 Machine Learning Models

Two classification algorithms are implemented in this project.

### 1. Logistic Regression

Logistic Regression is used as a baseline classification model because it is simple, efficient, and suitable for binary classification problems.

### 2. Random Forest Classifier

Random Forest is used to capture more complex relationships between features. It also provides feature importance, which helps identify the attributes that contribute most to the prediction.

---

## 🔄 Machine Learning Workflow

```text
Dataset
   ↓
Data Loading
   ↓
Data Exploration
   ↓
Data Cleaning
   ↓
Exploratory Data Analysis
   ↓
Feature & Target Separation
   ↓
Train-Test Split
   ↓
Feature Scaling
   ↓
Model Training
   ↓
Prediction
   ↓
Model Evaluation
   ↓
Model Comparison
   ↓
Final Analysis
