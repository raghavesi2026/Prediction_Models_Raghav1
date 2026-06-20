"# Prediction_Models_Raghav1" 
"# Perdiction-Model"

Machine Learning Internship Projects
Overview
This repository contains four Machine Learning projects developed during my internship. These projects demonstrate the complete ML workflow including:

Data Collection
Data Preprocessings
Feature Scaling
Train-Test Splitting
Model Training
Model Evaluation
Prediction on New Data
The projects cover both Classification and Regression problems using Scikit-Learn.

Projects Included
1. Diabetes Prediction System
Objective
Predict whether a patient is diabetic based on medical attributes.

Dataset Features
Pregnancies
Glucose
Blood Pressure
Skin Thickness
Insulin
BMI
Diabetes Pedigree Function
Age
Algorithms Used
Support Vector Machine (SVM)
StandardScaler
Evaluation Metric
Accuracy Score : 0.6883116883116883
Workflow
Load dataset
Data exploration and analysis
Feature scaling
Train-test split
Train SVM classifier
Evaluate model accuracy
Predict diabetes status for new patient data
2. Heart Disease Prediction System
Objective
Predict whether a person has heart disease using medical information.

Dataset Features
Age
Sex
Chest Pain Type
Resting Blood Pressure
Cholesterol
Fasting Blood Sugar
ECG Results
Maximum Heart Rate
Exercise Induced Angina
ST Depression
Number of Major Vessels
Thalassemia
Algorithms Used
Support Vector Machine (SVM)
StandardScaler
Evaluation Metric
Accuracy Score :
Workflow
Load dataset
Handle missing values
Encode categorical features
Feature scaling
Train-test split
Train SVM model
Evaluate accuracy
Predict heart disease for new patient data
3. House Price Prediction System
Objective
Predict house prices based on housing features.

Algorithms Used
Random Forest Regressor
StandardScaler
Data Processing
Outlier detection using IQR method
Feature scaling
Evaluation Metric
R² Score : 0.9426430733151114
Workflow
Load housing dataset
Remove outliers using IQR
Split features and target variable
Scale features
Train Random Forest model
Evaluate using R² Score
Predict house prices for new houses
4. Wine Quality Prediction System
Objective
Predict wine quality using physicochemical properties.

Dataset Features
Fixed Acidity
Volatile Acidity
Citric Acid
Residual Sugar
Chlorides
Free Sulfur Dioxide
Total Sulfur Dioxide
Density
pH
Sulphates
Alcohol
Algorithms Used
Random Forest Regressor
StandardScaler
Data Processing
Outlier removal using IQR method
Feature scaling
Evaluation Metric
R² Score : 0.25860192464920584
Workflow
Load wine quality dataset
Remove outliers
Feature scaling
Train-test split
Train Random Forest model
Evaluate performance
Predict wine quality
Technologies Used
Python
NumPy
Pandas
Scikit-Learn
Matplotlib
Jupyter Notebook
Google Colab
Machine Learning Concepts Implemented
Data Preprocessing
Feature Engineering
Feature Scaling
Outlier Detection
Classification
Regression
Support Vector Machine (SVM)
Random Forest Regression
Model Evaluation
Accuracy Score
R² Score
Installation
git clone https://github.com/adityamalaviya/ml-internship-projects.git

cd ml-internship-projects

pip install pandas numpy scikit-learn matplotlib
Run Project
python diabeticsinternship.py
python heart_disease.py
python house_price_internship.py
python wine_test.py
Future Improvements
Add GUI using Streamlit
Hyperparameter Tuning
Cross Validation
Model Serialization using Pickle
Deploy models using Flask/FastAPI
Add performance visualizations


Author
Raghav Rathod 

Diploma in Computer Engineering

Machine Learning Internship Projects
