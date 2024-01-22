# Machine-Learning-Model-Applied-to-Predict-Heart-disease

Predicting Heart Disease Using Machine Learning Model

A heart attack happens when the blood supply to the heart becomes significantly reduced or obstructed. The obstruction is typically caused by a buildup of fat, cholesterol, and other chemicals in the arteries leading to the heart (coronary). Plaques are the name given to these cholesterol- and fatty-rich formations. Atherosclerosis describes the process of plaque accumulation.
A plaque can rupture and generate a clot, which can obstruct blood flow. Part of the heart muscle might become damaged or even die if there is not enough blood flow.
A heart attack is sometimes referred to as a myocardial infarction.
About the Data Set
The offered data includes a table of patient data that includes age, gender, heart rate, systolic blood pressure, diastolic blood pressure, blood sugar, CK-MB, and troponin values. 100 patients with chest discomfort were treated at the hospital and provided with the data. To diagnose heart attacks, doctors need the data.
Individual patients are represented by the rows. The information for each patient is listed in the same order, from left to right.
The data is an important resource for clinicians since it can aid in the diagnosis and treatment of heart attacks. The information is also useful in the study of cardiac attacks.

## Data Loading and Exploration

The heart disease dataset is loaded into a pandas DataFrame
Basic exploration is done to check number of rows/columns, data types, summary statistics etc.

## Visualizations

Pie chart created to show gender distribution
Correlation matrix plotted to see relationships
Bar plot for disease status by gender

## Preprocessing

Features (X) and target (y) separated
Data split into 80% train and 20% test

## Modeling

### Multiple models tested:
Logistic Regression
Random Forest
Gaussian Naive Bayes
Decision Tree
Support Vector Machine
Each model initialized with standard settings/parameters
Models fit on training data and tested on held-out test set

## Evaluation
### Accuracy metric calculated for each model on the test set
Bar plot created to compare accuracy across models
Confusion matrices generated to analyze errors in detail
The analysis follows a standard machine learning workflow - loading data, exploratory visualization, preprocessing, training a variety of models, evaluating model accuracy, and analyzing errors. The steps provide a template for a typical machine learning predictive modeling project. The report also highlights some best practices like holdout test sets, stratified sampling, and proper model evaluation.
