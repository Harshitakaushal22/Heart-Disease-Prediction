# Heart Disease Prediction using Logistic Regression

This project aims to predict whether a patient is likely to have heart disease based on their medical parameters using a **Logistic Regression model**.

## 🔍 Objective

To develop a binary classification model that can predict the presence or absence of heart disease in patients using logistic regression, based on clinical attributes such as age, cholesterol, and blood pressure.

## 📁 Dataset

- **Filename**: `heart_disease.csv`
- **Features**:
  - `Age` – Patient's age
  - `Gender` – Male or Female
  - `Cholesterol` – Cholesterol level
  - `Blood Pressure` – Systolic/Diastolic pressure
  - `Heart Disease` – Target (1 = Yes, 0 = No)

## 🧠 Tasks Performed

1. **Data Preprocessing**
   - Handled missing values and duplicates
   - Converted categorical columns to numerical
   - Normalized numerical features like Age, Cholesterol, and BP

2. **Model Training**
   - Used Logistic Regression from `sklearn.linear_model`
   - Trained model on 80% of the dataset
   - Tested model on the remaining 20%

3. **Model Evaluation**
   - Evaluated using Confusion Matrix and classification report
   - Metrics computed: Accuracy, Precision, Recall, F1-score

## 📊 Evaluation Results

- **Model Used**: Logistic Regression  
- **Evaluation Metrics**:
  - **Accuracy**: **88.33%**
  - **Precision**:
    - Class 0 (No disease): 0.89  
    - Class 1 (Heart disease): 0.88
  - **Recall**:
    - Class 0: 0.91  
    - Class 1: 0.84
  - **F1-score**:
    - Class 0: 0.90  
    - Class 1: 0.86


