# Credit_Risk_Analysis

In this challenge, you’ll build and evaluate several machine learning models to assess credit risk, using data from LendingClub; a peer-to-peer lending services company.

The goals of this challenge are for you to:

Implement machine learning models.
Use resampling to attempt to address class imbalance.
Evaluate the performance of machine learning models.

### Naive Random Oversampling

The precision score are 1.00 for predicting low-risk and 0.01 for predicting high-risk. The recall score is about the same (~0.67) for both categories. The balanced accuracy score is 0.67, which is pretty low.

### SMOTE Oversampling
The precision score are 1.00 for predicting low-risk and 0.01 for predicting high-risk. The recall score is about the same (0.66 for low-risk and 0.69 for high-risk) for both categories. The balanced accuracy score is 0.68, which is pretty low.

### Undersampling
The precision score are 1.00 for predicting low-risk and 0.01 for predicting high-risk. The recall score is about the same (0.47 for low-risk and 0.71 for high-risk) for both categories. The balanced accuracy score is 0.59, which is low.

### Combination Sampling
The precision score are 1.00 for predicting low-risk and 0.01 for predicting high-risk. The recall score is about the same (0.62 for low-risk and 0.75 for high-risk) for both categories. The balanced accuracy score is 0.68, which is pretty low.

### Balanced Random Forest Classifier
The precision score are 1.00 for predicting low-risk and 0.04 for predicting high-risk. The recall score is about the same (0.91 for low-risk and 0.68 for high-risk) for both categories. The balanced accuracy score is 0.79, which is getting better than the other models.

### Easy Ensemble AdaBoost Classifier
The precision score are 1.00 for predicting low-risk and 0.08 for predicting high-risk. The recall score is about the same (0.95 for low-risk and 0.91 for high-risk) for both categories. The balanced accuracy score is 0.93, which is getting fairly high and trustworthy.

### Conclusion and Recommendations
Looking at all the different models, we observe that Easy Ensemble AdaBoost Classifier performs the best and therefore we should move forward with that model for further analysis. We notice that the recall score has the highest coefficients for predicting both low-risk and hogh risk loan status, meaning this would be our best model considering the high financial cost associated with False Negative in this case.
