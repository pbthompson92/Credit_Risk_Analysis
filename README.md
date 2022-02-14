# Credit Risk Analysis

## Overview 

The purpose of this analysis is to use multiple machine learning models or algorithms to evaluate the credit risk from LendingClub, a peer-to-peer lending services company. This analysis will help predict 'risky' versus 'good' loans. 

## Results 

### Naïve Random Oversampling 
![Naive Random Oversampling](https://user-images.githubusercontent.com/91712554/153800709-fb488780-6d23-4114-8e05-0ccb59fb0001.png)

 * Balanced Accuracy Score: 64.4%
 * Precision High Risk: 1%
 * Precision Low Risk: 100%
 * Recall High Risk: 69%
 * Recall Low Risk: 59%


 ### SMOTE Oversampling 
![Smote Oversampling](https://user-images.githubusercontent.com/91712554/153800739-7570202b-a7b3-427d-b7b8-5218d085a7cf.png)

 * Balanced Accuracy Score: 66.3%
 * Precision High Risk: 1%
 * Precision Low Risk: 100%
 * Recall High Risk: 63%
 * Recall Low Risk: 69%



 ### Cluster Centroids Undersampling
![Cluster Centroids Undersampling](https://user-images.githubusercontent.com/91712554/153800759-7787ae5d-41f9-4479-be47-07fa72f2625e.png)

 * Balanced Accuracy Score: 54.5%
 * Precision High Risk: 1%
 * Precision Low Risk: 100%
 * Recall High Risk: 69%
 * Recall Low Risk: 40%


 ### Combination (Over and Under) Sampling
![Combo Over and Under Sampling](https://user-images.githubusercontent.com/91712554/153800769-8f680ee9-d0d6-411e-a397-19b181212aae.png)

 * Balanced Accuracy Score: 63.9%
 * Precision High Risk: 1%
 * Precision Low Risk: 100%
 * Recall High Risk: 70%
 * Recall Low Risk: 57%


 ### Balanced Random Forest Classifier
![Balaned Random Forest Classifier](https://user-images.githubusercontent.com/91712554/153800776-c579f544-362a-4b74-81d9-33a1f0a20a34.png)

 * Balanced Accuracy Score: 78,9%
 * Precision High Risk: 3%
 * Precision Low Risk: 100%
 * Recall High Risk: 70%
 * Recall Low Risk: 87%



 ### Easy Ensemble AdaBoost Classifier 
![Easy Ensemble ADABoost Classifier](https://user-images.githubusercontent.com/91712554/153800782-952d6900-de0b-4628-9e80-7bbd27f0d0fd.png)

 * Balanced Accuracy Score: 93.1%
 * Precision High Risk: 9%
 * Precision Low Risk: 100%
 * Recall High Risk: 92%
 * Recall Low Risk: 94%


## Summary 

Overall, all of the above machine learning models are overfit. This is indicated by the high precision scores. Of all the models tested, the East Ensemble AdaBoost Classifier model is recommended as it has a high balanced accuracy score and a balance of precision and recall scores. 
