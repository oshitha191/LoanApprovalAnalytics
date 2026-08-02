LOAN APPROVAL ANALYTICS

## Overview 
Predicts loan approval using Decision Tree, Random Forest and Gradient Boosting with SHAP explainability and data preprocessing.

## Features
- Data preprocessing and feature engineering
- Trained and compared multiple ML models
- Evaluated models using Accuracy, F1-Score, and ROC-AUC
- Selected Random Forest as the best-performing model
- Applied Explainable AI using SHAP and Feature Importance
- Generated loan approval predictions

## Tech Stack
- Programming Language: Python
- Libraries: Pandas, NumPy, Scikit-learn, SHAP, Matplotlib, Seaborn
- Machine Learning Models: Random Forest, Bagging Classifier, Gradient Boosting, Decision Tree, Logistic Regression, k-Nearest Neighbors (kNN)
- Explainable AI (XAI): SHAP, Permutation Importance, Feature Importance, Partial Dependence Plots   (PDP)
- Development Environment: Jupyter Notebook / Google Colab

## Project Architecture
```mermaid
flowchart LR
    A[Dataset] --> B[Preprocessing]
    B --> C[Random Forest]
    C --> D[SHAP & XAI]
    D --> E[Loan Approval Prediction]
```


## Results:
- Best Model: Random Forest
- Accuracy: 97.89%
- F1-Score: 98.33%
- ROC-AUC: 0.9982
- Tree-based ensemble models achieved the best performance.

##  Screenshots


<img width="878" height="340" alt="Screenshot 2026-08-01 212322" src="https://github.com/user-attachments/assets/ff1556fe-3309-489c-b47b-a9ffb6c3cf25" />



<img width="715" height="511" alt="Screenshot 2026-08-01 212312" src="https://github.com/user-attachments/assets/b6ed4442-ddb6-4dc6-8961-e22c15ba0996" />











