# Credit_Risk_Analysis
## Overview of Project
LendingClub, a peer-to-peer lending services company, would like to develop a few machine learning models to predict credit risk. Credit risk is an unbalanced since the number of good loans outnumber the risky loans. Multiple techniques will be employed to determine which model(s) perform better at predicting credit risk. The dataset was first oversampled using the RandomOverSampler and SMOTE. The dataset was then undersampled using ClusterCentroids. SMOTEENN algorithm was used next which combines both over- and undersampling of the data.

## Results
* Naive Random Oversampling 

An accuracy score of 65.7%, a precision score of 1% for high-risk, and a 100% for low-risk. Recall score of 71% for high-risk and 60% for low-risk were produced with this model.


![Naive Random Oversampling](https://user-images.githubusercontent.com/67697826/213802447-e8d465fb-2b1a-439a-8850-785516b8e243.png)

* SMOTE Oversampling 
An accuracy score of 66.2%, a precision score is at 1% for high-risk, and a rate of 100% for low-risk. Recall score is 63% for high-risk and 69% for low-risk.

![SMOTE Oversampling](https://user-images.githubusercontent.com/67697826/213803238-2c048ff4-1bfa-4869-afd6-f47202b37e1a.png)

* Undersampling
An accuracy score of 54.4%, a precision score is at 1% for high-risk, and a rate 100% for low-risk. A recall score is 69% for high-risk and 40% for low-risk.

![Undersampling](https://user-images.githubusercontent.com/67697826/213804134-82293315-e678-44cb-a8e9-96593ebfd1a8.png)

* Combination (Over and Under) Sampling
An accuracy score of 68.8%, precision score is at 1% for high-risk, and a rate of 100% for low-risk. Recall score is 80% for high-risk and 57% for low-risk.

![Combination (Over and Under) Sampling](https://user-images.githubusercontent.com/67697826/213804719-68d346e7-9962-45a9-abdc-fa3aa96d1117.png)



## Summary
