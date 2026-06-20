##  Datasets Overview

### 1. Diabetes Prediction
- *File*: diabetes1.csv
- *Task*: Binary Classification
- *Target*: Outcome (0 = No Diabetes, 1 = Diabetes)
- *Features*: Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, Age
- *Model Trained*: Yes (Logistic Regression)

### 2. Heart Disease Prediction
- *File*: heart_disease.csv
- *Task*: Binary Classification
- *Target*: target (0 = No Disease, 1 = Disease)
- *Features*: age, sex, cp, trestbps, chol, fbs, restecg, thalach, exang, oldpeak, slope, ca, thal
- *Model Trained*: Yes

### 3. House Price Prediction
- *File*: house_prices.csv
- *Task*: Regression
- *Target*: price
- *Features*: sqft_living, bedrooms, bathrooms, floors, house_age, dist_to_city_km, quality_score
- *Model Trained*: Yes (Random Forest Regressor)

### 4. Weather Classification
- *File*: weather_classification_data.csv
- *Task*: Multi-class Classification
- *Target*: WeatherType (Sunny, Cloudy, Rainy, Snowy)
- *Features*: Temperature, Humidity, Wind Speed, Precipitation, Cloud Cover, Atmospheric Pressure, UV Index, Season, Visibility, Location
- *Model Trained*: Yes

### 5. Wine Quality Prediction
- *File*: winequality.csv
- *Task*: Regression / Multi-class Classification
- *Target*: quality (score from 3 to 9)
- *Features*: fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, free sulfur dioxide, total sulfur dioxide, density, pH, sulphates, alcohol
- *Model Trained*: Yes

##  Project Structure

```text
Machine-Learning-Projects
│
├── Diabetes
│   ├── Diabetes.ipynb
│   └── diabetes1.csv
│
├── Heart_Disease
│   ├── Heart_Disease.ipynb
│   └── heart_disease_data.csv
│
├── House_Price_Prediction
│   ├── House_Price.ipynb
│   └── house_prices.csv
│
├── Weather_Classification
│   ├── Weather_Classification.ipynb
│   └── weather_classification_data.csv
│
├── Wine_Quality
│   ├── Wine_Quality.ipynb
│   └── winequality.csv
│
└── README.md
```
