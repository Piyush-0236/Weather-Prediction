# 🌦️ Weather Classification using Machine Learning
This project demonstrates how to build a supervised machine learning model to classify weather conditions based on meteorological data. The goal is to predict categories such as Sunny, Rainy, Snowy, etc., using relevant features like temperature, humidity, visibility, pressure, and wind speed.

## 📌 Problem Statement
Weather prediction is a crucial part of various industries including agriculture, aviation, and disaster management. In this project, we approach weather classification as a multi-class classification problem using machine learning techniques. The model takes historical weather data as input and predicts the corresponding weather condition.

## 📊 Dataset
The dataset contains the following features:

Temperature (°C)

Humidity (%)

Wind Speed (km/h)

Visibility (km)

Pressure (kPa)

Weather Condition (Target)

The data was cleaned, normalized, and encoded appropriately to suit the ML model requirements.

## ⚙️ Technologies Used
Python

Jupyter Notebook

Pandas – for data manipulation

NumPy – for numerical operations

Matplotlib & Seaborn – for data visualization

Scikit-learn – for ML models and preprocessing

## 🧠 Machine Learning Model
The following steps were followed:

Data Preprocessing

Null value handling

Label encoding of categorical features

Feature scaling using StandardScaler

Train-Test Split

80% training and 20% testing

Model Training

Logistic Regression

Decision Tree Classifier

Random Forest Classifier

(Optional: SVM, k-NN, Naive Bayes can also be added)

Evaluation Metrics

Accuracy Score

Classification Report

Confusion Matrix

## 📈 Results
The Random Forest Classifier achieved the highest accuracy.

Clear distinction among classes was visible in the confusion matrix.

Feature importance visualization helped identify key factors influencing weather.

