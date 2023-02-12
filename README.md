# Credit Risk Analysis
Module 18 Challenge
## Objective 
The purpose of this analysis was to utilize credit card datasets from Lending Club, a peer-to-peer lending services company. Using linear regression to sample and predict the data utilizing different sampling techniques. The data was sampled and classified using these methods: 
  1. Naive Random Oversampling
  2. SMOTE Oversampling
  3. Cluster Centroid Undersampling
  4. SMOTEENN Sampling
  5. Balanced Random Forest Classifying
  6. Easy Ensemble Classifying

The same process was followed for each method:
  - split data intro training and testing datasets
  - compile accuracy scores
  - produce confusion matrix
  - produce classification reports

## Results

### Naive Random Oversampling
  - Accuracy Score: 65.4%
  - Precision High Risk: 1%
  - Precision Low Risk: 100%
  - Recall High Risk: 62%
  - Recall Low Risk: 69%

![image](https://user-images.githubusercontent.com/114044192/218338950-2a7f6630-8595-4fc6-b432-211e36ff409e.png)

### SMOTE Oversampling
  - Accuracy Score: 63.6%
  - Precision High Risk: 1%
  - Precision Low Risk: 100%
  - Recall High Risk: 62%
  - Recall Low Risk: 65%

![image](https://user-images.githubusercontent.com/114044192/218339361-82049b08-b473-4d20-a4b6-b682017498fd.png)

### Cluster Centroid Undersampling
  - Accuracy Score: 63.6%
  - Precision High Risk: 1%
  - Precision Low Risk: 100%
  - Recall High Risk: 59%
  - Recall Low Risk: 44%

![image](https://user-images.githubusercontent.com/114044192/218339447-421489e1-3d70-480a-8d17-0b41a599a0e7.png)


### SMOTEENN Sampling
  - Accuracy Score: 51.2%
  - Precision High Risk: 1%
  - Precision Low Risk: 100%
  - Recall High Risk: 70%
  - Recall Low Risk: 57%

![image](https://user-images.githubusercontent.com/114044192/218339537-56d709c3-9535-461c-9be4-764e8aa1b786.png)

### Balanced Random Forest Classifying
  - Accuracy Score: 88.8%
  - Precision High Risk: 3%
  - Precision Low Risk: 100%
  - Recall High Risk: 68%
  - Recall Low Risk: 89%

![image](https://user-images.githubusercontent.com/114044192/218339650-1528ae65-b9e7-4fc8-833f-0ae31eb00348.png)

### Easy Ensemble Classifying
  - Accuracy Score: 91.9%
  - Precision High Risk: 7%
  - Precision Low Risk: 100%
  - Recall High Risk: 90%
  - Recall Low Risk: 94%

![image](https://user-images.githubusercontent.com/114044192/218339752-76f460c8-05e9-443a-a5d1-374be84bd093.png)


## Summary

