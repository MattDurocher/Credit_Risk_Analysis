# Credit_Risk_Analysis
## Overview
Using machine learning, we were able to determine credit card risk using different algorithms (RandomOverSampler, SMOTE, ClusterCentroids, SMOTEENN, and BalancedRandomForestClassifier) to determine which model should used to predict credit risk.
## Results (high_risk/low_risk)
Naive Random Oversampling
- Balanced Accuracy: 0.6402889074215083
- Precision: 0.01/1.00
- Recall: 0.57/0.71

SMOTE Oversampling
- Balanced Accuracy: 0.6433276526825966
- Precision: 0.01/1.00
- Recall: 0.62//0.67

Undersampling
- Balanced Accuracy: 0.6433276526825966
- Precision: 0.01/1.00
- Recall: 0.61/0.44

Combination Sampling
- Balanced Accuracy: 0.6140249626325989
- Precision: 0.01/1.00
- Recall: 0.68/0.55

Balanced Random Forest Classifier
- Balanced Accuracy: 0.7877672625306695
- Precision: 0.04/1.00
- Recall: 0.67/0.91

Easy Ensemble AdaBoost Classifier
- Balanced Accuracy: 0.925427358175101
- Precision: 0.07/1.00
- Recall: 0.91/0.94

## Summary
When analyzing this data, it is clear to see that the Easy Ensemble AdaBoost Classifier algorithm is the most efficient model for balanced accuracy coming in at 0.925427358175101. For precision, every model was similar with there being a slight variation in the high_risk but, each low_risk being 1.0. Easy Ensemble AdaBoost Classifier also yields us the best result for recall with a score of 0.91/0.94. The last algorithm, the Easy Ensemble AdaBoost Classifier is the best model to work on. 
