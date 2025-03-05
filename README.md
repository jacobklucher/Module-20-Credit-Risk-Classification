# Module-20-Credit-Risk-Classification

## Overview of the Analysis

The purpose of this analysis was to evaluate different machine learning models for predicting loan classifications based on given financial data. The dataset used contained information about loan applicants such as loan size, interest rate, borrower income, number of accounts, any derogatory marks, total debt, and the loan status. The goal of this analysis was to determine if a loan should be classified as 0 (healthy loan) or 1 (high-risk loan).
The analysis involved the following steps:
* Separating the features and labels, and splitting the data into training and testing sets.
* Implementing and training each machine learning model:
	* Logistic Regression
	* Support Vector Machine (SVM)
	* Random Forest
* Evaluating each model based on accuracy, precision, and recall to determine the effectiveness of the model.

## Results

* Logistic Regression:
  * Accuracy Score: 99.27% 
  * Precision:
    * Class 0: 99%
    * Class 1: 95%
  * Recall:
    * Class 0: 100%
    * Class 1: 85%
* SVM
  * Accuracy Score: 99.36% 
  * Precision:
    * Class 0: 100%
    * Class 1: 84%
  * Recall:
    * Class 0: 99%
    * Class 1: 98%
* Random Forest
  * Accuracy Score: 99.16% 
  * Precision:
    * Class 0: 100%
    * Class 1: 85%
  * Recall:
    * Class 0: 99%
    * Class 1: 90%

## Summary

From the three models, the Support Vector Machine performed the best with the highest accuracy at 99.36% and a high recall percentage for predicting high-risk loans (1). The Random Forest model also performed well, with a moderately high recall value. The Logistic Regression model had a high accuracy but it had the lowest recall for high-risk loans of the three models used.
Considering that the models are predicting loan status outcomes, the most important factor should be identifying loans that are high-risk. This is shown by the recall score for the models. This means that my recommendation would be to use the SVM model as it has a superior recall for high-risk loans compared to the other models at 98% while also maintaining a strong overall accuracy score.
