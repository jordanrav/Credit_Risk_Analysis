# Credit_Risk_Analysis

## Overview of the analysis
the purpose of this Analysis is to use machine learning algorithms to predict whether a credit loan is a risky loan or a good loan

## Results

### Naive Random Sampling:

* Accuracy Score of 0.5875 suggests that the model correctly predicts the risk of a loan 58.75% of the time.
* Precision for the "high-risk" loans is 0.01, which means the model has a low ability to identify high-risk loans among all loans predicted as high-risk correctly.
* Recall for the "high-risk" loans is 0.72, meaning that the model correctly identifies 72% of the high-risk loans.

<img width="1138" alt="Screenshot 2023-02-02 at 10 18 04 AM" src="https://user-images.githubusercontent.com/112649072/216403995-ad521c74-c9aa-429d-befa-74a80c484f55.png">


### SMOTE Oversampling:

* Accuracy Score of 0.6900 suggests that the model correctly predicts the risk of a loan 69% of the time.
* Precision for the "high-risk" loans is 0.01, which means the model has a low ability to identify high-risk loans among all loans predicted as high-risk correctly.
* Recall for the "high-risk" loans is 0.63, meaning that the model correctly identifies 63% of the high-risk loans.

<img width="1136" alt="Screenshot 2023-02-02 at 11 43 10 AM" src="https://user-images.githubusercontent.com/112649072/216404156-f46c4c38-964a-4dda-9bde-4e25bb28caad.png">

### Cluster Centroids:

* Accuracy Score of 0.5787 suggests that the model correctly predicts the class of a loan 57.87% of the time.
* Precision for the "high-risk" loans is 0.01, which means the model has a low ability to identify high-risk loans among all loans predicted as high-risk correctly.
* Recall for the "high-risk" loans is 0.63, meaning that the model correctly identifies 63% of the high-risk loans.
<img width="604" alt="Screenshot 2023-02-02 at 11 42 21 AM" src="https://user-images.githubusercontent.com/112649072/216404237-54df7ebb-3867-4a38-a97f-2abd4a4257a0.png">


### SMOTEENN:

* Accuracy Score of 0.7189 suggests that the model correctly predicts the class of a loan 71.89% of the time.
* Precision for the "high-risk" loans is 0.01, which means the model has a low ability to identify high-risk loans among all loans predicted as high-risk correctly.
* Recall for the "high-risk" loans is 0.61, meaning the model correctly identifies 61% of the high-risk loans.
<img width="539" alt="Screenshot 2023-02-02 at 11 42 32 AM" src="https://user-images.githubusercontent.com/112649072/216404249-719e0487-c249-410e-b044-c685c6c7af74.png">


### Balanced Random Forest Classifier:

* Accuracy Score of 0.7903 suggests that the model correctly predicts the class of a loan 79.03% of the time.
* Precision for the "high-risk" loans is 0.02, which means the model has a moderate ability to identify high-risk loans among all loans predicted as high-risk correctly.
* Recall for the "high-risk" loans is 0.71, meaning the model correctly identifies 71% of the high-risk loans.

<img width="1131" alt="Screenshot 2023-02-02 at 11 43 43 AM" src="https://user-images.githubusercontent.com/112649072/216408231-40d51625-03a4-4225-bc73-9f1bb6ee1566.png">

### Easy Ensemble AdaBoost Classifier:

* Accuracy Score of 0.9524 suggests that the model correctly predicts the class of a loan 95.24% of the time.
* Precision for the "high-risk" loans is 0.07, which means the model has a moderate ability to identify high-risk loans among all loans predicted as high-risk correctly.
* Recall for the "high-risk" loans is 0.96, meaning that the model correctly identifies 96% of the high-risk loans.
<img width="1125" alt="Screenshot 2023-02-02 at 11 43 58 AM" src="https://user-images.githubusercontent.com/112649072/216408530-ea221592-86ca-43df-8c91-b91408ca0cf0.png">

## Summary
Based on this analysis's results, if you are looking for a high recall, then the Easy Ensemble AdaBoost Classifier Algorithm has been the best algorithm for that. Still, when it comes to precision, all of the algorithms had a low amount of precision, meaning that many safe loans will be considered high risk. So if a company is willing to deal with potentially lost customers, then id go with the Easy Ensemble AdaBoost Classifier Algorithm, but if you are not, then all these algorithms would not be good.

#### Side Note
Cluster Centroids and SMOTEENN are taken from google colab due to the fact that i was receiving an error in jupyter notebook


