### Overview of Analysis

Credit Risk Analysis of a large data set with 80+ factors that determine the risk of a loan as high or low.  Six machine learning models were applied to predict credit loan risks

Models used:
- Oversampling
- SMOTE
- Undersampling (Cluster Centroids)
- SMOTEENN
- Random Forest
- Easy Ensemble

### Results

## Oversampling:

Balanced Accuracy Score: 0.64

[img]

## SMOTE:

Balanced Accuracy Score: 0.66%

[img]

## Undersampling:

Balanced Accuracy Score: 0.66

[img]

## SMOTEENN

Balanced Accuracy Score: 0.62

[img]

## Random Forest

Balanced Accuracy Score: 0.79

[img]

## AdaBoost

Balanced Accuracy Score: 0.93

[img]

### Summary

These models are not the best for credit risk assessment.  The Recall value for some look promising (combination sampling) but the precision is lacking.  In conclusion, These models are great at predicting the high risk applicants but will result in false positives for classifying low risk applicants as high risk applicants.  With that inaccuracy, these models could be improved on. 