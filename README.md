# Credit_Risk_Analysis

## Overview
- Using different techniques to train and evaulate models to evaluate if a customer has good or bad credit.  Since our dataset is unbalanced we will have to use unbalanced libraries to build and evaluate the models.

## Results
### Over and Undersampling to predict Credit Risk
#### Naive Random Oversampling
Naive Random Oversampling model had an accuracy rating of 64%.  This model had a precision score of 1% for high risk credit and a 100% for low risk credit. The recall score of 72% for high risk credit and 56% for low risk credit.

![image](https://user-images.githubusercontent.com/109490755/219981871-1cb2d698-863e-4774-bcdc-87dd2fb4798a.png)

#### SMOTE Oversampling
SMOTE Oversampling model had a higher balanced accuracy score than the previous model at 66%.  This model had a precision score of 1% for high risk credit and 100% for low risk credit. The recall score for this model is 62% for high risk credit and 69% for low risk credit.  

![image](https://user-images.githubusercontent.com/109490755/219983079-6b0c7b0b-c7de-45b1-9008-e33469b32c00.png)

#### Undersampling
Undersampling using the ClusterCentroids model had a balanced accuracy score of 54%.  This model had a precision score of 1% for high risk credit and 100% for low risk credit.  The recall score is 69% for high risk and 40% for low risk credit.  

![image](https://user-images.githubusercontent.com/109490755/219985460-35377990-c750-459a-9830-d21878be30fb.png)

#### Combination (Over & Under) Sampling using SMOTEENN
Utilizing a combination of over and under sampling using SMOTEEN resulted in a balanced accuracy score of 67%.  This model had a precision score of 1% for high risk credit and 100% for low risk credit.  The recall score is 73% and 60% for high and low risk credit respectively.  

![image](https://user-images.githubusercontent.com/109490755/219985537-890a5f73-5739-4540-9b76-0d02f27b4e11.png)

### Ensemble Classifiers to predict Credit Risk
#### Balanced Random Forest Classifier
#### Easy Ensemble AdaBoost Classifier

## Summary
- Summary of the results
- recommendation of which model to use or no recommendation with Justification
