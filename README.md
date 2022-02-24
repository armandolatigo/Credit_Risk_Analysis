### Overview of Analysis

Credit Risk Analysis of a large data set with 80+ factors that determine the risk of a loan as high or low.  Six machine learning models were applied to predict credit loan risks

Models used:
- Oversampling
- SMOTE
- Undersampling (Cluster Centroids)
- SMOTEENN
- Random Forest
- Easy Ensemble

### Results

## Oversampling:

Balanced Accuracy Score: 0.64

![OVERsamp](https://user-images.githubusercontent.com/92451164/155600129-c8128181-00f9-4c59-a6ac-ff71a51040a8.png)

## SMOTE:

Balanced Accuracy Score: 0.66%

![SMOTE](https://user-images.githubusercontent.com/92451164/155600159-9508e0e2-fc9e-43ea-a087-89898b293157.png)

## Undersampling:

Balanced Accuracy Score: 0.66

![undersamp](https://user-images.githubusercontent.com/92451164/155600202-207d0d67-a8ed-4b3d-980a-ff009ea0c538.png)

## SMOTEENN

Balanced Accuracy Score: 0.62

![smoteeen](https://user-images.githubusercontent.com/92451164/155600224-86428830-7cf0-4790-97bc-15089418d95e.png)

## Random Forest

Balanced Accuracy Score: 0.79

![randomforest](https://user-images.githubusercontent.com/92451164/155600259-3a172501-25bf-4095-84e8-755e7ca9bd32.png)

## AdaBoost

Balanced Accuracy Score: 0.93

![EasyEns](https://user-images.githubusercontent.com/92451164/155600320-11549e0e-a4a1-4fd2-906e-0d7dceb71c6f.png)

### Summary

These models are not the best for credit risk assessment.  The Recall value for some look promising (combination sampling) but the precision is lacking.  In conclusion, These models are great at predicting the high risk applicants but will result in false positives for classifying low risk applicants as high risk applicants.  With that inaccuracy, these models could be improved on. 
