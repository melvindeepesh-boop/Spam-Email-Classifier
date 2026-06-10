# Spam Email Classifier

## Overview

This project is a Machine Learning-based Spam Email Classifier that predicts whether an email is Spam or Not Spam using the Multinomial Naive Bayes algorithm.

## Dataset

The dataset contains email word frequencies and a target column named **Prediction**:

* 0 = Not Spam
* 1 = Spam

## Technologies Used

* Python
* Pandas
* Scikit-Learn
* Google Colab

## Project Workflow

### 1. Data Loading

* Uploaded and extracted the dataset from a ZIP file.
* Loaded the dataset using Pandas.

### 2. Data Exploration

* Viewed dataset using:

  * head()
  * tail()
  * shape
  * columns
  * info()
  * describe()
  * isnull().sum()

### 3. Feature Selection

Separated the dataset into:

* X (input features)
* y (target variable)

### 4. Train-Test Split

Split the dataset into:

* 80% Training Data
* 20% Testing Data

### 5. Model Training

Used the Multinomial Naive Bayes algorithm to learn patterns from email word frequencies.

### 6. Prediction

Generated predictions on unseen test data.

### 7. Model Evaluation

Evaluated model performance using Accuracy Score.

## Results

* Algorithm: Multinomial Naive Bayes
* Accuracy: 95.46%

## Conclusion

The model successfully classifies emails as Spam or Not Spam with high accuracy. This project demonstrates the complete machine learning workflow, including data preprocessing, model training, prediction, and evaluation.

## Author

Deepesh M
