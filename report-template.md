## Credit Risk Analysis Report

The purpose of this analysis was to use Logistic Regression in order to train and evaluate a model based on loan risk. We used a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

As part of the machine learning process, following steps were followed:
* Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.
* Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.
* Split the data into training and testing datasets by using train_test_split.
* Fit a logistic regression model by using the training data (X_train and y_train).
* Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.
* Evaluate the model’s performance by doing the following:
    * Generate a confusion matrix.
    * Print the classification report.

## Results

* Accuracy Score - 0.99
* Precision Score (Weighted Avg) - 0.99
* Recall Score (Weighted Avg) - 0.99

## Summary

The accuracy rate of this model for predicting loan risk is excellent at 99%, however its precision and recall scores for high-risk loans are noticibly lower than those of the predicted healthy loans. The model could be improved by feeding it more high-risk borrower data in order for it to better learn and make more accurate predictions.  Despite these slight deficiencies, the model created could still be recommended for the purpose of evaluating loan risk.
