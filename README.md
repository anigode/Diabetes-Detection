Diabetes Prediction Project
1.	Diabetes Prediction This project implements a machine learning model to predict diabetes outcomes based on medical diagnostic measurements. The analysis involves data preprocessing, model training, and evaluation using three different machine learning algorithms: Decision Tree, Random Forest, and Logistic Regression.
2.	Table of Contents
•	Introduction
•	Installation
•	Usage
•	Data
•	Models
•	Evaluation
•	Libraries
•	License
3.	Introduction The goal of this project is to classify whether a patient has diabetes based on diagnostic measures such as the number of pregnancies, glucose levels, blood pressure, and other medical measurements. The project utilizes data exploration, preprocessing, and various machine learning models to predict diabetes outcomes effectively.
4.	Installation To set up the project, clone the repository and install the required libraries. Ensure you have Python installed (preferably version 3.6 or above).
5.	Usage
•	Place your dataset CSV file (e.g., diabetes.csv) in the project directory.
•	Run the diabetes_prediction.py script to execute the analysis.
•	The processed data will be saved as data.csv in the project directory.
6.	Data
•	The project uses a dataset containing various medical diagnostic measurements, which includes features such as:
•	Pregnancies: Number of times pregnant
•	Glucose: Plasma glucose concentration a 2 hours in an oral glucose tolerance test
•	BloodPressure: Diastolic blood pressure (mm Hg)
•	SkinThickness: Triceps skin fold thickness (mm)
•	Insulin: 2-Hour serum insulin (mu U/ml)
•	BMI: Body mass index (weight in kg/(height in m)^2)
•	DiabetesPedigreeFunction: Diabetes pedigree function
•	Age: Age (years)
•	Outcome: Class variable (0 or 1) indicating whether the patient has diabetes
•	The script performs the following data preprocessing steps:
•	Replaces zero values in SkinThickness and Insulin columns with NaN and fills NaN values with the median of the respective columns.
•	Visualizes the distribution of pregnancies and histograms of features.
•	Creates a correlation matrix to identify relationships between features and the target variable.
7.	Models The following machine learning models are implemented in this project:
•	Decision Tree Classifier: A tree-based model that makes predictions based on feature splitting.
•	Random Forest Classifier: An ensemble method that combines multiple decision trees to improve accuracy.
•	Logistic Regression: A statistical model that predicts the probability of a binary outcome based on independent variables.
Each model's performance is evaluated using accuracy scores and classification reports.
8.	Evaluation The performance of each model is evaluated based on:
•	Accuracy: The ratio of correctly predicted instances to the total instances.
•	Classification Report: A detailed report including precision, recall, and F1-score for each class.
9.	Libraries The project depends on the following Python libraries:
•	pandas
•	numpy
•	seaborn
•	matplotlib
•	sklearn

