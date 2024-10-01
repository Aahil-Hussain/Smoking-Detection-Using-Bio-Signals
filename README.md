# Smoking-Detection-Using-Bio-Signals

# Project Overview
This project aims to develop an intelligent system that can predict the presence or absence of smoking habits in individuals based on their bio-signal data. The dataset contains various physiological measurements and biomarkers, which are used to train machine learning models for prediction.
The management seeks to use the collected bio-signal data to automatically identify smokers. This system could help in medical assessments or workplace health monitoring, where understanding smoking habits can be critical.

## Dataset
The dataset consists of multiple bio-signal features related to the individual's physical characteristics and health metrics. The key features include:

- gender: Male or Female.
- age: Age of the individual.
- height(cm): Height in centimeters.
- weight(kg): Weight in kilograms.
- waist(cm): Waist circumference.
- eyesight(left/right): Visual acuity in the left and right eye.
- hearing(left/right): Hearing ability in the left and right ear.
- hemoglobin: Hemoglobin level in the blood.
- urine protein: Presence of protein in urine.
- serum creatinine: Level of serum creatinine.
- AST: Aspartate aminotransferase, a liver enzyme.
- ALT: Alanine aminotransferase, another liver enzyme.
- The target variable is a label indicating whether the individual is a smoker or not.

# Objective
The goal is to use bio-signals to classify individuals into smokers and non-smokers, leveraging a variety of health and biometric features. This system can aid in preventive healthcare, diagnostics, and wellness programs.

# Steps Performed

## Data Preprocessing:
- Label Encoding: Categorical variables (like gender) were label encoded to convert them into numerical values suitable for machine learning models.
- Handling Outliers and Null Values: Appropriate measures were taken to handle missing values and remove outliers to ensure data quality and model performance.

## Exploratory Data Analysis (EDA):
- Heatmap Visualization: A correlation heatmap was created to identify significant relationships between the bio-signal features and the target variable (smoking status). This helped in understanding feature importance.

## Feature Selection:
- Recursive Feature Elimination with Cross-Validation (RFE_CV): This technique was used to identify the most important features for predicting smoking habits. RFE helped reduce irrelevant features and optimized the model's performance through cross-validation.

## Modeling Approach
- The data was split into training and testing sets, and a classification model was built using the selected features. The primary focus was on understanding the importance of each bio-signal feature and how it impacts the smoking prediction.

## Performance Evaluation
- Different evaluation metrics were used to assess the model, including accuracy, precision, recall, and F1-score. Cross-validation ensured that the  model performed consistently across different subsets of the data.

## Modeling Approach
- The data was split into training and testing sets, and several classification models were built, with Logistic Regression being the primary model evaluated.

## Logistic Regression Model Performance
Accuracy: 71.74%
Precision, Recall, and F1-Score:

# Results:
The Logistic Regression model shows a good overall accuracy of 71.74%, with the recall for smokers being particularly high (92%), indicating the model is effective at identifying smokers.
