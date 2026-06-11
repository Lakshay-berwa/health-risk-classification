# health-risk-classification
A machine learning project for predicting patient health risks using data preprocessing, feature engineering, classification models, and performance evaluation techniques.
# Patient Health Risk Prediction using Machine Learning

## Project Overview

This project aims to predict disease risk in patients using machine learning techniques. The workflow includes data cleaning, missing value treatment, exploratory data analysis (EDA), outlier handling, feature encoding, model training, hyperparameter tuning, and performance evaluation.

The objective is to identify patients who may be at higher risk of disease based on various health-related attributes.

---

## Dataset Features

The dataset contains patient health information such as:

- Patient ID
- Age
- Gender
- BMI
- Blood Pressure
- Cholesterol
- Glucose
- Region
- Disease Risk (Target Variable)

---

## Project Workflow

### 1. Data Preprocessing
- Missing value analysis
- Mean Imputation
- Most Frequent Imputation
- Random Sample Imputation
- KNN Imputation
- MICE (Iterative Imputer)

### 2. Exploratory Data Analysis (EDA)
- Count Plot
- Histograms
- Correlation Heatmap
- Boxplots

### 3. Feature Engineering
- Label Encoding
- Missing Value Indicators

### 4. Outlier Treatment
- Z-Score Analysis
- IQR Method
- Capping
- Winsorization

### 5. Data Scaling
- StandardScaler

### 6. Machine Learning Models
- Logistic Regression
- Decision Tree Classifier
- K-Nearest Neighbors (KNN)
- Random Forest Classifier
- XGBoost Classifier

### 7. Hyperparameter Tuning
- GridSearchCV on Random Forest

### 8. Model Evaluation
- Accuracy Score
- Precision Score
- Recall Score
- F1 Score
- ROC-AUC Score

---

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn
- XGBoost

---

## Project Structure

---

## Results

Multiple classification algorithms were trained and compared. The best-performing model was selected based on evaluation metrics such as Accuracy, Precision, Recall, F1-Score, and ROC-AUC.

---

## Future Improvements

- Deploy model using Flask or Streamlit
- Add feature importance visualization
- Improve hyperparameter tuning
- Implement advanced ensemble techniques

---

## Author

Lakshay

Machine Learning & Data Science Project
