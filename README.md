# Credit Risk Analysis
## Overview
The purpose of this project was to use supervised machine learning models to predict the amount of risk in giving a loan, classifying the loans a good or bad. Six machine learning models were tested, and the balanced accuracy score, precision, and recall were compared to determine the best model to use to predict credit risk. 

## Results
* Model 1: RandomOverSampler
  * Balanced accuracy: 0.640544738146174
  * Precision: 0.99
  * Recall: 0.69 
* Model 2: SMOTE
  * Balanced Accuracy: 0.6369822449448252
  * Precision: 0.99
  * Recall: 0.64 
* Model 3: Cluster Centroids
  * Balanced Accuracy: 0.5292150629907619
  * Precision: 0.99 
  * Recall: 0.45
* Model 4: SMOTEENN
  * Balanced Accuracy: 0.6377870037991871
  * Precision: 0.99 
  * Recall: 0.58
* Model 5: Balanced Random Forest Classifier
  * Balanced Accuracy: 0.9544339291973362
  * Precision: 1.00
  * Recall: 0.91
* Model 6: Easy Ensemble Classifier
  * Balanced Accuracy: 0.9645835599550383
  * Precision: 1.00
  * Recall: 0.95

## Summary
While all of the models are able to sort the loans into good or bad in terms of credit risk, the model that I would recommend is the Easy Ensemble Classifier as it has the highest precision, recall, and balanced accuracy. 
