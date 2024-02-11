# House Loan Approval Prediction System
## Overview
This Python-based project focuses on predicting house loan approvals using machine learning techniques. The system utilizes several libraries, including Pandas, Matplotlib, Scikit Learn, and NumPy, to analyze and model the data. The predictive models employed in this project are Decision Tree Classifier, Logistic Regression, Random Forest Classifier, and Naïve Bayes Classifier.

## Dataset
The dataset comprises three CSV files:
- Train File: Used for model training, containing both independent variables and the target variable.
- Test File: Contains independent variables without the target variable. The trained models will be applied to predict the target variable for this data.
- Sample Submission File: Provides the required format for submitting predictions.

## Models and Accuracy
The accuracy of various classifiers in our project is 
- Decision Tree Classifier: Accuracy - 68.18%
- Logistic Regression: Accuracy - 77.27%
- Random Forest Classifier: Accuracy - 77.99%
- Naïve Bayes Classifier: Accuracy - 82.93%

Therefore, the Naïve Bayes Classifier is selected for its higher accuracy, making it the preferred model for predicting house loan approvals.

## Naïve Bayes Classifier
- Naive Bayes is a simple classification algorithm that uses probabilities to categorize items.
- It assumes that features are independent and calculates the probability of an item belonging to a class based on its features.
- The class with the highest probability is the predicted class.
