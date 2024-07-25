# Heart Disease Prediction Using Logistic Regression

## Overview

This project involves predicting the presence of heart disease using logistic regression. The model was built from scratch using mathematical equations, and the final accuracy achieved is 79.51%. The dataset used for this project is a publicly available heart disease dataset.

## Data Description

The dataset contains various features related to patient health and is used to predict the presence or absence of heart disease. Below is a description of each feature in the dataset:

- **age**: Age in years
- **sex**: Gender (1 = Male, 0 = Female)
- **cp**: Chest Pain Types
  - 0 = Typical Angina
  - 1 = Atypical Angina
  - 2 = Non-anginal pain
  - 3 = Asymptomatic
- **trestbps**: Resting blood pressure (in mm Hg)
- **chol**: Serum Cholesterol (in mg/dl)
- **fbs**: Fasting Blood Sugar > 120 mg/dl (1 = true, 0 = false)
- **restecg**: Resting ECG results
  - 0 = normal
  - 1 = abnormality ST-T wave abnormality
  - 2 = Showing probable or definite left ventricular hypertrophy by Estes' criteria
- **thalach**: Maximum Heart Rate Achieved
- **exang**: Exercise Induced Angina (1 = Yes, 0 = No)
- **oldpeak**: ST depression induced by exercise
- **slope**: Slope of Peak Exercise ST
  - 0 = Unsloping
  - 1 = Flat
  - 2 = Downsloping
- **ca**: Number of Major Vessels (0-3) (Fluoroscopy)
- **thal**: Thalassemia
  - 1 = Normal
  - 2 = Fixed defect
  - 3 = Reversible defect
- **target**: Presence or absence of disease (1 = Yes, 0 = No)

## Model Implementation

The logistic regression model was implemented from scratch using the following steps:

1. **Data Preprocessing**:
   - Loaded and split the dataset into training and testing sets.
   - Standardized the features using `StandardScaler`.

2. **Model Training**:
   - Implemented logistic regression using gradient descent.
   - Calculated cost and gradients to update model parameters.

3. **Prediction**:
   - Used the trained model to make predictions on the test set.
   - Calculated the accuracy of the model.

4. **Evaluation**:
   - Evaluated the model's performance using accuracy and confusion matrix.
