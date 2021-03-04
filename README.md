# Credit_Risk_Analysis

## Overview
The purpose of the credit risk analysis is to use credit data from the peer-to-peer lending service company, LendingClub, to predict the predict the risk a creditor provides. 

## Results
There is a bulleted list that describes the balanced accuracy score and the precision and recall scores of all six machine learning models (15 pt)
### Naive Random Oversampling with Logistic Regression
- Balanced Accuracy Score: 0.61
- Precision: 0.99
- Recall: 0.65

### SMOTE Oversampling with Logistic Regression
- Balanced Accuracy Score: 0.58
- Precision: 0.99
- Recall: 0.69

### Undersampling with Logistic Regression
- Balanced Accuracy Score: 0.57
- Precision: 0.99
- Recall: 0.63

### Combination (Over and Under) Sampling with Logistic Regression
- Balanced Accuracy Score: 0.62
- Precision: 0.99
- Recall: 0.57

### Balanced Random Forest Classifier
- Balanced Accuracy Score: 0.69
- Precision: 0.99
- Recall: 0.87

### Easy Ensemble AdaBoost Classifier
- Balanced Accuracy Score: 0.70
- Precision: 0.99
- Recall: 0.80

## Summary
- The models have accuracy in the 0.57 to the 0.70 range. 
- The precision is 0.99 for all, indicating that when a risky creditor is identified they are nearly guarenteed to be a risky creditor.
- However, the recall ranges from 0.57 to 0.87. This is problematic, as it means some of the models barely identify most of the risky creditors.

The Balanced Random Forst Classifier is the best model, followed by the Easy Ensemble AdaBoost Classifier. The RFC shows a high precision and high recall, meaning it's resutls can be easily trusted. The EEABC shows similarly high statistics, being beaten by the RFC in recall. 
