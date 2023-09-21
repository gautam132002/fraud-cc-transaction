# Credit Card Fraud Detection with Logistic Regression

This repository presents a machine learning model for credit card fraud detection, specifically utilizing Logistic Regression, with the provided dataset.

## Dataset

The dataset used for this project can be found at the following URL: [Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/kartik2112/fraud-detection).

## Colab Notebook

For a detailed implementation and analysis of the credit card fraud detection model using Logistic Regression, please refer to the Colab notebook available here: [Colab Notebook](https://colab.research.google.com/drive/1y7dx0EjWemwOMTSRbd0Psxkg83XAlsZz#scrollTo=QT5aH56ccy9y).

## Selected Columns

We have chosen the following columns from the dataset for our analysis:
- "amt"
- "category"
- "gender"
- "city_pop"
- "cc_num"
- "job"
- "unix_time"
- "merch_lat"
- "merch_long"
- "is_fraud"

## Categorical Columns

The following columns are treated as categorical variables in our analysis:
- "category"
- "gender"
- "job"

## Logistic Regression

Logistic Regression is the machine learning algorithm used for this credit card fraud detection model. It's a binary classification algorithm well-suited for fraud detection tasks, where the goal is to classify transactions as either fraudulent or legitimate.

## Model Accuracy

Our machine learning model, based on Logistic Regression, achieved an accuracy of 84% in detecting credit card fraud.

Please feel free to explore, modify, and adapt this project for your own credit card fraud detection tasks. 
