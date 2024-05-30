**Loan-Eligibility-Prediction:

A Python Project for Data Science: Loan Eligibility Prediction. Through this project, I developed a Loan Eligibility Prediction model using Python, implemented popular Machine Learning algorithms, and explored various Python libraries.

**Libraries Used
Pandas: Powerful and fast, used for data analysis, manipulation, and filtering.
NumPy: Used to perform mathematical and logical operations on arrays.
Matplotlib: Used for static, interactive, and data visualization.
Scikit-learn: A comprehensive library with efficient tools for machine learning and statistical modeling, including a range of supervised and unsupervised learning algorithms.
Project Overview
For this project, I utilized a supervised learning algorithm: Naive Bayes Classification.

**Steps to Approach the Dataset:
Import Necessary Libraries: Load essential Python libraries.

Import and Analyze Data: Load the dataset and analyze it for missing values and outliers using boxplots.

Handle Missing Values: Normalize the data. Use log functions for missing value handling or fill these values using mode for categorical data and mean for numerical data.

Split Data: Divide the dataset into training and testing sets (x_train, x_test, y_train, y_test).

Encode Categorical Data: Convert categorical data into numerical format (0s and 1s) using Label Encoder for both training and testing data.

Train Classifier: Use the Naive Bayes classifier, which provided an accuracy of 82.788%, higher than the decision tree accuracy of 70.34%.

Attribute Selection: Select the best attributes from the dataset based on entropy, information gain, Gini index, gain ratio, and other metrics.

Normalize Testing Data: Apply the same normalization and missing value handling procedures to the testing data as used with the training data.

Encode Testing Data: Convert the categorical data of the testing dataset into numerical format.

Predict Loan Eligibility: Finally, predict the loan eligibility status (label) of the testing data.

This project provided a comprehensive learning experience in data preprocessing, handling missing values, feature selection, and model training and evaluation. By comparing different algorithms, I was able to select the most effective one for this particular dataset.
