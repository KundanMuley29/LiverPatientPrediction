# Liver Patient Prediction (LPP)

This repository contains a machine learning project to identify whether a patient has abnormal liver functioning based on various medical test results. It uses the Indian Liver Patient Dataset (ILPD) for analysis, visualization, and model building.

## Dataset

- **Source**: Indian Liver Patient Dataset (ILPD)
- **Attributes**:
  - Age
  - Gender
  - Total Bilirubin
  - Direct Bilirubin
  - Alkaline Phosphotase
  - Alamine Aminotransferase
  - Aspartate Aminotransferase
  - Total Proteins
  - Albumin
  - Albumin and Globulin Ratio
  - Target: 1 = Liver Disease, 2 = No Liver Disease

## Project Workflow

1. **Data Preprocessing**:
   - Loaded and cleaned dataset
   - Handled missing values
   - Renamed columns for readability

2. **Exploratory Data Analysis (EDA)**:
   - Distribution of target classes
   - Visualized feature distributions
   - Correlation analysis

3. **Model Building** :
   - Train/test split
   - Built classification models (Logistic Regression, Random Forest, XGboost.)
   - Evaluated using metrics like accuracy, precision, recall

## Result 
* Logistic Regression:-              precision    recall  f1-score   support

           1       0.79      0.84      0.81        88
           2       0.39      0.31      0.35        29

    accuracy                           0.71       117
   macro avg       0.59      0.58      0.58       117
weighted avg       0.69      0.71      0.70       117

[[74 14]
 [20  9]]
Accuracy: 0.7094017094017094

* Random Forest:-  precision    recall  f1-score   support

           1       0.80      0.82      0.81        88
           2       0.41      0.38      0.39        29

    accuracy                           0.71       117
   macro avg       0.60      0.60      0.60       117
weighted avg       0.70      0.71      0.71       117

[[72 16]
 [18 11]]
Accuracy: 0.7094017094017094

* XGboost:- precision    recall  f1-score   support

           1       0.78      0.81      0.79        88
           2       0.35      0.31      0.33        29

    accuracy                           0.68       117
   macro avg       0.56      0.56      0.56       117
weighted avg       0.67      0.68      0.68       117

[[71 17]
 [20  9]]
Accuracy: 0.6837606837606838
