**Heart Disease Prediction**


Overview

This project aims to predict the presence of heart disease in a patient based on various medical attributes. Using machine learning algorithms, the model analyzes patient data to assess the likelihood of heart disease, thereby aiding healthcare professionals in early diagnosis and treatment planning.

**Features**


Data Preprocessing: Handling missing values, data normalization, and feature selection.
Exploratory Data Analysis (EDA): Visualization and statistical analysis to understand the data distribution and relationships.
Model Building: Implementation of various machine learning algorithms such as Logistic Regression, Decision Trees, Random Forests, and Support Vector Machines.
Model Evaluation: Performance metrics including accuracy, precision, recall, F1-score, and ROC-AUC.
Hyperparameter Tuning: Optimization techniques to improve model performance.

Dataset

The dataset used in this project is sourced from the UCI Machine Learning Repository. It consists of 14 attributes, including:

Age
Sex
Chest Pain Type (4 values)
Resting Blood Pressure
Serum Cholesterol in mg/dl
Fasting Blood Sugar > 120 mg/dl
Resting Electrocardiographic Results (values 0,1,2)
Maximum Heart Rate Achieved
Exercise Induced Angina
ST Depression Induced by Exercise Relative to Rest
Slope of the Peak Exercise ST Segment
Number of Major Vessels (0-3) Colored by Fluoroscopy
Thal (3 = normal; 6 = fixed defect; 7 = reversible defect)



Installation


To get started with this project, clone the repository and install the required dependencies:


git clone https://github.com/yourusername/heart-disease-prediction.git

cd heart-disease-prediction

pip install -r requirements.txt


Run the following command to train the model and evaluate its performance:

python train_model.py

To make predictions on new data, use:

python predict.py --input new_data.csv
