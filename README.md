# Flight_fare_prediction_app


[Introduction](#introduction)

[Data Source](#data-source)

[Steps to build App](#steps-to-build-app)

[Saving Model](#saving-model)

[Deployment to cloud](#deployment-to-cloud)


I have deployed this end to end Machine Learning project on Heroku to predict the flight ticket price using Flask web API

The web app can be accessed by following URL:

https://flight-price-ml-app.herokuapp.com/

# Introduction

The objective of this project is to predict the flight ticket price using given flights data with different airlines between various Indian cities. I have used this dataset to make a useful end to end machine learning web application to know the flight fare in advance to plan the travel dates according to varying price of tickets.

# Data Source

https://www.kaggle.com/nikhilmittal/flight-fare-prediction-mh

# Steps to build App

Data Selection 
 
Performing Exploratory Data analysis (EDA)
 
Data Transformation (Categorical data, Missing data etc. )
 
Selecting Machine learning algorithm based on EDA
 
Creating Train and Test Split 
 
Creating the Model

Model accuracy

Hyper parameter Tuning to achieve better accuracy
     
        
   1) RandomizedSearchCV --> Fast
   
   2) GridSearchCV

Assign hyperparameters in form of dictionary

Fit the model

Check best parameters and best score


# Saving Model

Use pickle to save the model

# Deployment to Cloud

Required Files

── static 
│   ├── css

├── templates
│   ├── index.html

├── Procfile

├── README.md

├── app.py

├── Flights-Fare-Prediction-ML.ipynb

├── rfModelPrediction.pkl

├── requirements.txt






