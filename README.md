# Loan Prediction Model

This project uses **Logistic Regression** to predict loan approval status (`Loan_Status`) based on applicant demographic and financial details. It is designed for binary classification and is trained on data from a loan eligibility dataset.

## Project Overview

The goal is to build a **machine learning model** that can automatically predict whether a loan should be approved or not based on historical data.

** Data Science Stack:
- Python (Jupyter Notebook)
- Scikit-learn
- Pandas, NumPy, Matplotlib, Seaborn

## Files Included

| File                     | Description |
|--------------------------|-------------|
| `loan_prediction.ipynb` | Main notebook with EDA, preprocessing, model training & prediction |
| `train.csv`             | Training dataset |
| `test.csv`              | Test dataset used for final predictions |
| `model.joblib`          | Saved logistic regression model using Joblib |
| `loan_predictions.csv`  | Final predictions made on test data |
| `README.md`             | Project overview |


## Key Steps:

1. **Import Libraries**

2. **Load Datasets**

3. **Exploratory Data Analysis (EDA)**:
   - Data overview and structure
   - Summary statistics
   - Checked for missing values
   - Visualized target class data distribution
   - Explored variable relationships using heatmaps.

4. **Data Cleaning and Preprocessing**:
   - Handled missing values
   - Treating outliers
   - Feature engineering (e.g. `TotalIncome`, `DebtToIncome`, log transforms)
   - Encoded categorical variables
   - Feature scaling

5. **Model Building and Training**:
   - Split Data
   - Applied **Logistic Regression**
   - Evaluated using accuracy, confusion matrix, and classification report

6. **Prediction**:
   - Applied model to preprocessed test data
   - Saved predictions to CSV
   - Saved trained model using Joblib

## Model Performance

- **Model**: Logistic Regression
- **Accuracy**: ~79% on validation data

