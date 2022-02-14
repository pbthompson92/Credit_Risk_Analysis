# Credit Risk Analysis

## Overview 

The purpose of this analysis is to use multiple machine learning models or algorithms to evaluate the credit risk from LendingClub, a peer-to-peer lending services company. This analysis will help predict 'risky' versus 'good' loans. 

## Results 

 # Naïve Random Oversampling 


 * Balanced Accuracy Score: 64.4%
 * Precision High Risk: 1%
 * Precision Low Risk: 100%
 * Recall High Risk: 69%
 * Recall Low Risk: 59%


 # SMOTE Oversampling 


 * Balanced Accuracy Score: 66.3%
 * Precision High Risk: 1%
 * Precision Low Risk: 100%
 * Recall High Risk: 63%
 * Recall Low Risk: 69%



 # Cluster Centroids Undersampling


 * Balanced Accuracy Score: 54.5%
 * Precision High Risk: 1%
 * Precision Low Risk: 100%
 * Recall High Risk: 69%
 * Recall Low Risk: 40%


 # Combination (Over and Under) Sampling


 * Balanced Accuracy Score: 63.9%
 * Precision High Risk: 1%
 * Precision Low Risk: 100%
 * Recall High Risk: 70%
 * Recall Low Risk: 57%


 # Balanced Random Forest Classifier


 * Balanced Accuracy Score: 78,9%
 * Precision High Risk: 3%
 * Precision Low Risk: 100%
 * Recall High Risk: 70%
 * Recall Low Risk: 87%



 # Easy Ensemble AdaBoost Classifier 


 * Balanced Accuracy Score: 93.1%
 * Precision High Risk: 9%
 * Precision Low Risk: 100%
 * Recall High Risk: 92%
 * Recall Low Risk: 94%


## Summary 

Overall, all of the above machine learning models are overfit. This is indicated by the high precision scores. Of all the models tested, the East Ensemble AdaBoost Classifier model is recommended as it has a high balanced accuracy score and a balance of precision and recall scores. 