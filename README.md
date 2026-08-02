LOAN APPROVAL ANALYTICS

## Overview 
Predicts loan approval using Decision Tree, Random Forest and Gradient Boosting with SHAP explainability and data preprocessing.

## Project Architecture
```mermaid
flowchart LR
    A[Dataset] --> B[Data Preprocessing]
    B --> C[Exploratory Data Analysis]
    C --> D[Feature Engineering]
    D --> E[Train-Test Split]

    E --> F[Model Training]
    F --> G1[Random Forest]
    F --> G2[Bagging]
    F --> G3[Gradient Boosting]
    F --> G4[Decision Tree]
    F --> G5[Logistic Regression]
    F --> G6[kNN]

    G1 --> H[Model Evaluation]
    G2 --> H
    G3 --> H
    G4 --> H
    G5 --> H
    G6 --> H

    H --> I[Best Model Selection]
    I --> J[Explainable AI]
    J --> K1[SHAP]
    J --> K2[Feature Importance]
    J --> K3[Permutation Importance]
    J --> K4[PDP]

    K1 --> L[Loan Approval Prediction]
    K2 --> L
    K3 --> L
    K4 --> L
```


## Results:
<img width="878" height="340" alt="Screenshot 2026-08-01 212322" src="https://github.com/user-attachments/assets/ff1556fe-3309-489c-b47b-a9ffb6c3cf25" />



<img width="715" height="511" alt="Screenshot 2026-08-01 212312" src="https://github.com/user-attachments/assets/b6ed4442-ddb6-4dc6-8961-e22c15ba0996" />


## Tech Stack
Programming Language: Python
Libraries: Pandas, NumPy, Scikit-learn, SHAP, Matplotlib, Seaborn
Machine Learning Models: Random Forest, Bagging Classifier, Gradient Boosting, Decision Tree, Logistic Regression, k-Nearest Neighbors (kNN)
Explainable AI (XAI): SHAP, Permutation Importance, Feature Importance, Partial Dependence Plots (PDP)
Development Environment: Jupyter Notebook / Google Colab










