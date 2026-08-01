LOAN APPROVAL ANALYTICS

Predicts loan approval using Decision Tree, Random Forest and Gradient Boosting with SHAP explainability and data preprocessing.

## Project Architecture
```mermaid
flowchart LR
A[Dataset] --> B[Preprocessing]
B --> C[Train Test Split]
C --> D[Model Training]
D --> E[Evaluation]
E --> F[Best Model Random Forest]
F --> G[XAI SHAP Feature Importance]
```
```

## Model Results & Insights

Evaluated multiple ML models, where ensemble methods outperformed others.

Best Model: Random Forest
  Accuracy: 97.89%, F1: 98.33%, ROC-AUC: 0.9982→ best balance & performance

Second: Bagging (RF base)
  Accuracy: 97.50%, highest precision → fewer false positives

Gradient Boosting & Decision Tree
  Similar performance but slightly lower generalization

Logistic Regression & kNN
  Lower scores → dataset has non-linear patterns

 Key insight observed:
Tree-based ensembles work best due to complex feature relationships.



## Explainable AI (XAI)

Applied on top 2 models using Feature Importance, Permutation Importance, SHAP, and PDP:

- Consistent top features across methods → robust model behavior
-  SHAP explains individual predictions clearly
-   PDP shows non-linear feature impact
-   

## Results:
<img width="715" height="511" alt="Screenshot 2026-08-01 212312" src="https://github.com/user-attachments/assets/6ee56902-9d4f-4e77-8d19-c5d197645539" />
<img width="878" height="340" alt="Screenshot 2026-08-01 212322" src="https://github.com/user-attachments/assets/9f28e279-bad4-4f64-acc0-740ea57e1580" />




## Conclusion

Random Forest selected as final model due to best overall performance.
Achieved 98% accuracy with explainability, ensuring reliability for real-world use.








