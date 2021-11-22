# Credit_Risk_Analysis

### Analysis Overview
This analysis uses a variety of supervised machine learning models to predict credit risk. The provided data set from LendingClub includes credit applicants, a variety of information about the applicant and their credit history, and the result of their application. Each machine learning model will be evaluated for accuracy, precision, and recall relative to the others to determine which model should be used by the client.

### Results

##### Naive Random Oversampling

![Naive Random OVersampling](https://user-images.githubusercontent.com/86164867/142918951-238f652c-544e-4435-b8e4-f8ed90aeb48f.PNG)
Accuracy Score: 66.88%
Precision (High Risk): 0.01
Precision (Total): 0.99
Recall (High Risk): 0.69
Recall (Total): 0.64

##### SMOTE Oversampling

![SMOTE](https://user-images.githubusercontent.com/86164867/142918874-d032be0d-1edd-41fb-b3b8-51a75dd77761.PNG)
Accuracy Score: 66.34%
Precision (High Risk): 0.01
Precision (Total): 0.99
Recall (High Risk): 0.63
Recall (Total): 0.69


##### Cluster Centroids Undersampling

![Cluster_Centroids](https://user-images.githubusercontent.com/86164867/142918820-081b2abe-de12-41d2-a189-25be7bf7c375.PNG)
Accuracy Score: 54.43%
Precision (High Risk): 0.01
Precision (Total): 0.99
Recall (High Risk): 0.69
Recall (Total): 0.40


##### SMOTEEN Combination Sampling

![smoteen](https://user-images.githubusercontent.com/86164867/142918720-5f3ddaa8-8152-435d-8097-2de6260086a5.PNG)
Accuracy Score: 67.74%
Precision (High Risk): 0.01
Precision (Total): 0.99
Recall (High Risk): 0.79
Recall (Total): 0.56


##### Balanced Random Forest Classifier

![Balanced_Random_Forest](https://user-images.githubusercontent.com/86164867/142918625-9334eaaa-c061-48f5-b1b9-946a4e542d88.PNG)
Accuracy Score: 78.85%
Precision (High Risk): 0.03
Precision (Total): 0.99
Recall (High Risk): 0.70
Recall (Total): 0.87


##### Easy Ensemble AdaBoost Classifier

![Easy_Ensemble](https://user-images.githubusercontent.com/86164867/142918517-6b23a050-6b3a-4eab-9512-f44295c6870a.PNG)
Accuracy Score: 93.17% 
Precision (High Risk): 0.09
Precision (Total): 0.99
Recall (High Risk): 0.92
Recall (Total): 0.94
