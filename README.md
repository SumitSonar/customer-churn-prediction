## Author: Sumit Sonar

### Project Overview
I developed a supervised learning model to predict customer churn for a telecommunications company. The dataset contains 7043 records and includes features such as `gender`, `SeniorCitizen`, `Partner`, `Dependents`, `tenure`, `PhoneService`, `InternetService`, `MonthlyCharges`, `TotalCharges`, and more. The goal was to predict whether a customer would churn or not, using models like **Logistic Regression** and **Decision Tree Classifier**. By analyzing customer demographics, usage patterns, and service history, I implemented and compared these models to find the most accurate one for predicting churn.

### How It Works
I began by preprocessing the data to ensure it's clean and ready for modeling. Since the `TotalCharges` column had some invalid values, I converted it to a numeric type and filled missing values with the median. I encoded categorical features such as `gender`, `Partner`, `PhoneService`, and `Churn` using label encoding, while columns with multiple categories like `Contract` and `PaymentMethod` were one-hot encoded. After splitting the dataset into training and testing sets, I trained the models and evaluated their performance based on accuracy, confusion matrix, and classification report. This allowed me to compare the models and choose the most effective one for predicting customer churn.
