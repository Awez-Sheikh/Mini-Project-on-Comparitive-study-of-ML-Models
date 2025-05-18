# Mini-Project-on-Comparitive-study-of-ML-Models
This project focuses on predicting diabetes using the **Pima Indians Diabetes Dataset**, which contains medical data of 768 female patients including 8 features such as glucose level, blood pressure, insulin, BMI, and age. The goal is to classify whether a patient is diabetic based on these attributes.

# Dataset Overview
Source: [Kaggle - Pima Indians Diabetes Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)

Records: 768

Features: 8 input variables + 1 target (Outcome: diabetic or not)


# Data Preprocessing
Missing Values: Zero entries in features like Glucose and BloodPressure replaced with median values.

Feature Scaling: Applied StandardScaler for normalization.

Train-Test Split: Dataset split 80% for training and 20% for testing.


# Classification Algorithms Applied
Logistic Regression: Achieved \~76.6% accuracy, high precision and recall.

Naive Bayes: Moderate accuracy (\~75.3%), quick and efficient.

KNN: Accuracy: \~74.7%, performance impacted by neighbor dependency.

Decision Tree: 72.7% accuracy, risk of overfitting.

Random Forest: \~76% accuracy, robust performance due to ensemble learning.

K-Means (Clustering): Low ARI score (\~0.136), not ideal for classification.


# Conclusion
Logistic Regression and Random Forest provided the best results, balancing simplicity and model performance for diabetes prediction.
