# Module 12 Report Template

## Overview of the Analysis

* Explain the purpose of the analysis.
    The purpose of this analysis is to build a model that can identify whether a crediter is a high or low risk.
* Explain what financial information the data was on, and what you needed to predict.
    A dataset of historical lending activity from a peer-to-peer lending services company was used
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
    "value_counts" was used to check whether a loan was high or low risk via a binary outcome, and used as a based to predict them in the future.
* Describe the stages of the machine learning process you went through as part of this analysis.
    Data was split into traning and test sets. Then, we define our dependent and independent variables. Next, we create logistic regression model and fit our original data to this model. Trained model is used to make predictions. Lastly, we evaluate the model`s performance.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).
    Two diffeent Logistic Regression models were created by using the original data set and randomy over resampled data set (to get rid of the imbalances). In the end, their results -which was gathered with scikit-learn library- were compared.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
Accuracy:
![image](https://github.com/Rdslatez/credit-risk-classification/assets/124850150/56db71a9-b426-48ab-9aab-1d7d1edd0f01)
![image](https://github.com/Rdslatez/credit-risk-classification/assets/124850150/9ed8572c-6e8d-4091-8f50-d7c6d016b248)




* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
Accuracy:
  ![image](https://github.com/Rdslatez/credit-risk-classification/assets/124850150/ed90682a-8c03-4928-aa49-eddafa16924a)
  ![image](https://github.com/Rdslatez/credit-risk-classification/assets/124850150/f0abbf59-0476-4797-9001-68bedddb5c10)



## Summary

Overall the data is shown to be useful for machine learning models, though it's clear the random oversampling of the data works best with higher balance and recall scores.
The results need to have a good accuracy for predicting both 1's and 0's values, because false positives would mean high-risk loans appearing like low-risk (dangerous) and low-risk looking like high-risk (loss of business).
