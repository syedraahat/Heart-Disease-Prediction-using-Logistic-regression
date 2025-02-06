# Heart Disease Prediction

This project focuses on predicting the presence of heart disease in patients using various health features. The dataset used for this project is based on real-world medical data and contains various attributes such as age, blood pressure, cholesterol levels, and others.

## Dataset

The dataset used for this project is the **Heart Disease Dataset** from kaggle

- `age`: Age of the patient
- `sex`: Gender (1 = male, 0 = female)
- `cp`: Chest pain type (1-4)
- `trestbps`: Resting blood pressure (in mm Hg)
- `chol`: Serum cholesterol (in mg/dl)
- `fbs`: Fasting blood sugar (> 120 mg/dl)
- `restecg`: Resting electrocardiographic results (0-2)
- `thalach`: Maximum heart rate achieved
- `exang`: Exercise induced angina (1 = yes, 0 = no)
- `oldpeak`: Depression induced by exercise relative to rest
- `slope`: Slope of the peak exercise ST segment (0-2)
- `ca`: Number of major vessels colored by fluoroscopy (0-3)
- `thal`: Thalassemia type (1-3)
- `target`: 1 if the patient has heart disease, 0 if not

## Project Overview

The main objective of this project is to predict whether a patient has heart disease based on the features provided. This is a supervised classification problem, and logistic regression was used as the model for prediction.

### Steps Involved:
1. **Data Preprocessing**: Clean the dataset by checking for missing values, removing unwanted columns, and preparing it for training.
2. **Exploratory Data Analysis (EDA)**: Analyze the dataset to get insights into the distribution of features.
3. **Modeling**: Train a logistic regression model on the dataset and evaluate its performance.
4. **Prediction**: Use the trained model to make predictions on both training and testing data.
5. **User Input Prediction**: Allow users to input their own health data to predict the presence of heart disease.
