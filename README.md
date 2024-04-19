# Fraud Detection System

Anonymized credit card transactions labeled as fraudulent or genuine


# **About Dataset**

Link to Kaggle Dataset - https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/data

# **Project Description**

This project aims to develop a credit card fraud detection system using various preprocessing techniques and classification algorithms. Here's a brief summary of the project:

## Data Understanding and Preprocessing:

Explored the dataset to understand its characteristics.
Preprocessed the data by scaling and splitting it into training and test sets.

## Random UnderSampling and Oversampling:

Implemented random undersampling to balance the class distribution.
Conducted anomaly detection and dimensionality reduction using t-SNE.
Trained classifiers such as Logistic Regression, K-Nearest Neighbors, Support Vector Classifier, and Decision Tree Classifier.
Utilized techniques like SMOTE (Synthetic Minority Over-sampling Technique) for oversampling.

## Testing:

Evaluated the performance of classifiers using cross-validation techniques.
Conducted testing with Logistic Regression and Neural Networks (undersampling vs. oversampling).
Analyzed confusion matrices to assess model performance.
Preprocessing and Modelling Techniques Used:

## Preprocessing:

Scaling and Distributing: Ensured features were on the same scale and data was evenly distributed for training and testing.
Splitting the Data: Separated the dataset into training and testing subsets to evaluate model performance.

## Modelling:

Random UnderSampling: Balanced class distribution by randomly removing samples from the majority class.
SMOTE (Synthetic Minority Over-sampling Technique): Generated synthetic samples to oversample the minority class and address class imbalance.

Classification Algorithms: Utilized various classifiers including Logistic Regression, K-Nearest Neighbors, Support Vector Classifier, and Decision Tree Classifier to train and test the data.

## Why These Techniques:

Preprocessing: Scaling ensures that features contribute equally to model training, while splitting the data enables unbiased evaluation of model performance.

Modelling: Random UnderSampling and SMOTE were chosen to address class imbalance, ensuring that the model learns from both classes effectively. Multiple classifiers were tested to identify the best-performing model for fraud detection.

Overall, this project demonstrates the importance of preprocessing techniques and model selection in developing an effective credit card fraud detection system.
