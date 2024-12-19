Problem Statement
This project focuses on Breast Cancer Recurrence Prediction. The goal is to analyze a dataset, "breast_cancer_data.csv", containing clinical and pathological factors that influence the recurrence of breast cancer. The objective is to explore, preprocess, and model the data to understand the factors contributing to recurrence and to build a machine learning model to predict whether a patient will experience recurrence events.

Dataset Description
The dataset contains the following columns:

age: Age of the patient (ranges: 30-39, 40-49, 50-59, 60-69).
menopause: Menopause status of the patient (premeno, ge40, lt40).
tumor-size: Size of the tumor (ranges in mm).
inv-nodes: Number of involved lymph nodes (ranges).
node-caps: Presence of node caps (yes or no).
deg-malig: Degree of malignancy (values: 1, 2, 3).
breast: Breast involved (left or right).
breast-quad: Quadrant of the breast involved (left_up, left_low, right_up, right_low, central).
irradiat: Whether the patient received irradiation (yes or no).
class: Target variable indicating recurrence of breast cancer (no-recurrence-events or recurrence-events).
Objectives
Data Exploration:

Understand the distribution and relationships between features.
Identify potential issues such as missing data or outliers.
Class Imbalance Handling:

Analyze the distribution of the target variable.
Apply techniques like oversampling (SMOTE), undersampling, or class-weighted modeling to address class imbalance.
Feature Engineering:

Encode categorical variables.
Standardize or normalize numerical features where necessary.
Model Building:

Train and evaluate machine learning models to predict breast cancer recurrence.
Compare different classifiers (e.g., Logistic Regression, Decision Trees, Random Forests, SVMs, etc.).
Evaluate performance using metrics like accuracy, precision, recall, F1-score, and ROC-AUC.
Insights:

Derive insights into the factors most strongly associated with breast cancer recurrence.
