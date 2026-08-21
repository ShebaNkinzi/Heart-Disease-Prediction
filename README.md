#  Heart Disease Prediction using Machine Learning

## Project Overview
This project focuses on predicting the presence of heart disease in patients based on various medical and physiological indicators. Using machine learning classification algorithms, this project aims to assist healthcare professionals in early diagnosis and risk assessment, ultimately aiding in better patient care and treatment planning.

This project was developed as part of the **Data Mining and Business Intelligence** practical examination at Uganda Martyrs University.

## Dataset
The dataset used in this project contains medical records of patients, including features such as age, sex, chest pain type, resting blood pressure, cholesterol levels, and more. 

- **Source:** Kaggle / UCI Machine Learning Repository
- **Target Variable:** `target` (1 = Presence of Heart Disease, 0 = Absence of Heart Disease)
- **Features:**
  - `age`: Age in years
  - `sex`: (1 = male; 0 = female)
  - `cp`: Chest pain type
  - `trestbps`: Resting blood pressure (in mm Hg)
  - `chol`: Serum cholestoral in mg/dl
  - `fbs`: Fasting blood sugar > 120 mg/dl (1 = true; 0 = false)
  - `restecg`: Resting electrocardiographic results
  - `thalach`: Maximum heart rate achieved
  - `exang`: Exercise induced angina (1 = yes; 0 = no)
  - `oldpeak`: ST depression induced by exercise relative to rest
  - `slope`: The slope of the peak exercise ST segment
  - `ca`: Number of major vessels (0-3) colored by flourosopy
  - `thal`: 3 = normal; 6 = fixed defect; 7 = reversable defect

## Methodology
The project follows a standard data mining pipeline:

1. **Data Loading & Exploration:** Loaded the dataset and performed initial exploratory data analysis (EDA) to understand the distribution of features.
2. **Data Preprocessing:** Handled missing values, encoded categorical variables, and normalized numerical features to ensure optimal model performance.
3. **Model Building:** Trained and evaluated two classification models:
   - **Logistic Regression** (Baseline model)
   - **Random Forest Classifier** (Ensemble model for better accuracy and feature importance)
4. **Model Evaluation:** Compared models using Accuracy, Precision, Recall, and F1-Score.
5. **Feature Importance:** Identified the top 3 most critical features influencing heart disease prediction.

## Author Sheba Nkinzi
