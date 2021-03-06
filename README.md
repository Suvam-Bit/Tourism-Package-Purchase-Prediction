# Tourism-Package-Purchase-Prediction

## Heroku App
Web-App Link: https://tour-pack-purchase-pred.herokuapp.com/

## Problem Statement
Tourism is one of the most rapidly growing global industries and tourism forecasting is becoming an increasingly important activity in planning and managing the industry. Because of high fluctuations of tourism demand, accurate predictions of purchase of travel packages are of high importance for tourism organizations.

## Approach
The classical machine learning tasks like Data Exploration, Data Cleaning, Feature Engineering, Model Building and Model Testing. Try out different machine learning algorithms that’s best fit for the above case.

## Result
The goal is to predict whether the customer will purchase the travel or not.

## Dataset
https://github.com/Suvam-Bit/Datasets/blob/main/Tourism%20Package%20Purchase%20Prediction/tourism-data.xlsx

## Data Description
CustomerID :	Unique customer ID

ProdTaken : 	Product taken flag

Age :	Age of customer

TypeofContact :   How the customers was contacted

CityTier:	City tier

DurationOfPitch :	Duration of pitch by a sales man to customer

Occupation :	Occupation of customer

Gender :	Gender of customer

NumberOfPersonVisited :	Total number of person came with customer

NumberOfFollowups :	Total number of follow up has been done by sales person after sales pitch

ProductPitched :	Product pitched by sales person

PreferredPropertyStar :	Preferred hotel property rating by customer

MaritalStatus :	Marital status of customer

NumberOfTrips :	Average number of trip in a year by customer

Passport :	Customer passport flag

PitchSatisfactionScore :	Sales pitch satisfactory score

OwnCar :	Customers owns a car flag

NumberOfChildrenVisited :	Total number of children visit with customer

Designation :	Designation of customer in current organization

MonthlyIncome :	Gross monthly income of customer

## Data Preprocessing
1. Exploratory Data Analysis
2. Univariate and Bivariate Visualization
3. Outlier Removal
4. Missing Value Imputation
5. One-Hot Encoding
6. Feature Transformation
7. Over Sampling - SMOTE

## Model Fitting
1. Logistic Regression
2. Random Forest Classifier
3. XGboost Classifier
4. SVM Classifier
5. KNN Classifier
6. CatBoost Classifier

#### NOTE:
Here we will use Recall instead of Accuracy because we're more interested in correctly classifying the records where target variable is 1.

## Hyper-parameter Tuning
1. Grid Search CV
2. Randomized Search CV

## Best Model
K-nearest Neighbors with highest Recall: 93.65%

## Model Deployment
Deployed the model using Flask on Heroku platform.
