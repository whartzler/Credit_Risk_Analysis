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
Balanced Rendom Forest Classifier had the second highest balanced accuracy score of 79% out of all the models.  This models precision score is 3% for high risk credit and 100% for low risk credit, a 2% increase over the previous models.  The Recall was also higher with 70% for high risk and 87% for low risk credit.

![image](https://user-images.githubusercontent.com/109490755/219986529-1956e8cf-6567-41ef-a8b7-321aebd36eea.png)

#### Easy Ensemble AdaBoost Classifier
Easy Ensemble AdaBoost Classifier was the most successful model with a balanced accuracy score of 93%.  The precision score also increased with a high risk at 9% and low risk again at 100%,  the high risk increased from the Ensemble Classifiers model by 7%.  The Recall scores also greatly improved with a 92% for high risk and 94% for low risk credit.

![image](https://user-images.githubusercontent.com/109490755/219986556-410fb4cf-c9c1-4fbb-8573-848909a3314f.png)

## Summary
Overall the resampling models did not do a great job at predicting high risk credit scores.  Through each model they had a precision of 1% for high risk,  this is a low score as the test came back positive but only 1% were likely to have high risk credit.  The ensemble classifiers were more accurate in accuracy, precision and recall.  

The best model was clearly the Easy Ensemble AdaBoost Classifier with all higher scores in accuracy, precision and recall due to its high Balanced Accuracy score and precision and recall scores.
