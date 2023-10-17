# Heart Attack Analysis and Prediction

## Introduction

This project focuses on analyzing and predicting heart attacks using the Heart Attack Analysis and Prediction dataset. The dataset is available on Kaggle [here](https://www.kaggle.com/rashikrahmanpritom/heart-attack-analysis-prediction-dataset) and on the UCI Machine Learning Repository [here](http://archive.ics.uci.edu/ml/datasets/Heart+Disease).

## Dataset Dictionary

The dataset contains the following attributes:

* `age`: Age of the patient.
* `sex`: Gender of the patient (1 = male; 0 = female).
* `cp`: Type of chest pain (0 = typical angina, 1 = atypical angina, 2 = non-anginal pain, 3 = asymptomatic).
* `trtbps`: Resting blood pressure (in mm Hg).
* `chol`: Cholesterol in mg/dl measured via BMI sensor.
* `fbs`: Fasting blood sugar (fasting blood sugar > 120 mg/dl) (1 = True, 0 = False).
* `restecg`: Resting electrocardiographic results (0 = normal, 1 = ST-T wave abnormality, 2 = left ventricular hypertrophy).
* `thalachh`: Maximum heart rate achieved.
* `oldpeak`: Previous peak.
* `slp`: Slope of the ST segment.
* `ca`: Number of major vessels in the heart (0-3).
* `thall`: Thalium stress test result (0-3).
* `exng`: Exercise-induced angina (1 = Yes, 0 = No).
* `output`: Target variable (0 = less chance of a heart attack, 1 = more chance of a heart attack).

## Objective

The goal of this project is to perform exploratory data analysis (EDA) and predict whether a person is prone to a heart attack or not.

## Data Analysis and Preprocessing
### This project performs data analysis and preprocessing, including:

* Data visualization using libraries like Matplotlib and Seaborn.
* Descriptive statistics.
* Handling missing data.
* Feature selection.
 
## Building and Training Models
### Three different models are built and trained:

1. Initial Neural Network Model
2. Model with Standardization
3. Model with Feature Selection

Each model is evaluated and compared for robustness.

## Grid Search
A grid search is performed to tune hyperparameters for model optimization. This search is done using 10-fold cross-validation.

## Robustness Analysis
The robustness of the models is analyzed by adding noise to the dataset. Three different noise levels are introduced to observe the models' performance in such conditions.
