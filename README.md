# Pima Indians Diabetes Classification

End-to-end ML project comparing logistic regression and random forest 
for diabetes prediction.

## Dataset
- Pima Indians Diabetes (768 patients, 8 clinical features)
- Imputed physiologically impossible zeros using column medians

## Models
| Model | Accuracy | AUC |
|-------|----------|-----|
| Logistic Regression | 70.1% | 0.813 |
| Random Forest | 77.9% | 0.819 |

## Key findings
Top predictive features (Random Forest): Glucose, BMI, DiabetesPedigree, Age — 
consistent with established T2DM risk factors.

## Notes
Built as a first hands-on ML project to ramp up on methods used in healthcare 
outcomes research.
