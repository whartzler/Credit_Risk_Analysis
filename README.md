# Credit_Risk_Analysis

## Overview
- Using different techniques to train and evaulate models to evaluate if a customer has good or bad credit.  Since our dataset is unbalanced we will have to use unbalanced libraries to build and evaluate the models.

## Results
### Over and Undersampling to predict Credit Risk
#### Oversampling
##### Naive Random Oversampling
Naive Random Oversampling model had an accuracy rating of 64% where it detected 64% of high risk credit.  Based on the data below Precsion was high for the majority class low_risk credit and low for high_risk credit.  It was great at predicting who actually had low_risk credit and how accurate the prediction was.  Where this model faultered was recall.  It did okay at measuring both types of credit in how they were correctly classified as having low or high risk credit.
![image](https://user-images.githubusercontent.com/109490755/219981871-1cb2d698-863e-4774-bcdc-87dd2fb4798a.png)

##### SMOTE Oversampling
SMOTE Oversampling model had a higher accuracy score than the previous model of 66% as it detected 66% of high risk credit.
![image](https://user-images.githubusercontent.com/109490755/219983079-6b0c7b0b-c7de-45b1-9008-e33469b32c00.png)

#### Undersampling
#### Combination (Over & Under) Sampling using SMOTEENN

### Ensemble Classifiers to predict Credit Risk
#### Balanced Random Forest Classifier
#### Easy Ensemble AdaBoost Classifier



## Summary
- Summary of the results
- recommendation of which model to use or no recommendation with Justification
