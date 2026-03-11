# Car Price Prediction using Machine Learning

## Overview
This project focuses on predicting vehicle prices using machine learning regression algorithms. The model analyzes different vehicle characteristics such as model, year, mileage, fuel type, and engine size to estimate the price of a car.

The objective of the project is to train and compare multiple regression models and determine which algorithm performs best for predicting car prices.


## Dataset
The dataset contains information about different vehicles and their prices.

Each record includes features such as:

- model
- year
- transmission
- mileage
- fuelType
- tax
- mpg
- engineSize

Target variable:
price

Dataset used in this project is stored in the repository as:
car_data.csv

Dataset shape:(17965,9)


## Technologies Used
The project was implemented using the following tools and libraries:

- Python
- Pandas
- NumPy
- Scikit-learn


## Machine Learning Models Used
The following regression models were trained and evaluated:

- Linear Regression
- K-Nearest Neighbors Regressor
- Support Vector Regressor (SVR)
- Random Forest Regressor

Among these models, KNN Regressor achieved the best performance with the highest R² score.


## Project Workflow
The main steps followed in this project are:

1. Load the dataset
2. Perform data cleaning
3. Encode categorical variables
4. Split the dataset into training and testing sets
5. Train multiple regression models
6. Evaluate model performance using R² score
7. Compare models and select the best performing model


## Files in this Repository
car_price_prediction.ipynb – Jupyter notebook containing the full implementation  
car_data.csv – Dataset used for training the model


## Conclusion
This project demonstrates how machine learning regression algorithms can be used to predict vehicle prices based on various features. Among the tested models, KNN Regressor provided the best prediction performance for this dataset.
