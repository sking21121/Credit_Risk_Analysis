# Credit_Risk_Analysis
# Overview of the analysis:
Apply machine learning to solve a real-world challenge: credit card risk.

Employ different techniques to train and evaluate models with unbalanced classes.

The credit card dataset is from LendingClub, a peer-to-peer lending services company.

Use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

---------------------------------------------------------------



Deliverable 1: Use Resampling Models to Predict Credit Risk

Deliverable 2: Use the SMOTEENN Algorithm to Predict Credit Risk

Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk



# Results:

![Screen Shot 2021-10-24 at 6 49 13 PM](https://user-images.githubusercontent.com/86200136/138616084-6531d01c-11a3-4a23-b920-4b40e9aec277.png)






# Summary:
Based on the Balanced Accuracy Score the Easy Ensemble AdaBoost Classifier was the highest at 93%. The highest Precision
score of 88% went to the Balanced Random Forest Classifier. This score is not as important in credit card risk becuase 
all the False Positives can be ruled out by calling back the credit card holders. The best Recall score went to 
Easy Ensemble AdaBoost Classifier at 92%. This score is due to a low number of False Negatives.

My recommendation is to use the Easy Ensemble AdaBoost Classifier based on the high Balanced Accuracy Score and
Recall score. This technique had the lowest count of False Negatives. 
