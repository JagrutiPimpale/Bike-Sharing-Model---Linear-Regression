# Project Name
Building a Multiple Linear Regression Model for Predicting Demand for Shared Bikes

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- Provide general information about your project here.
The goal of the project is to create a multiple linear regression model to forecast the demand for shared bikes for BoomBikes, a US bike-sharing company. Understanding the elements influencing the demand for shared bikes in the American market and how well they capture the demand for bikes are the main objectives. The model should be developed using the 'cnt' variable as the goal variable. The dataset provides daily bike needs across the American market based on some criteria. The management will utilise the model to comprehend how demand changes with different features and adjust business strategy as necessary to meet demand levels and satisfy consumer expectations. Before applying the model, the data preparation process entails transforming some feature values into category string values.

- What is the background of your project
BoomBikes, a US bike-sharing company, seeks to comprehend how the Covid-19 outbreak has affected demand for rented bikes in the US market. The project entails developing a model to estimate demand for shared bikes using available independent factors in order to assist management in adjusting the business strategy to meet demand levels and consumer expectations. The model should be developed using the 'cnt' variable as the goal variable. The dataset provides daily bike needs across the American market based on some criteria.

- What is the business probem that your project is trying to solve?
BoomBikes, a US bike-sharing company, has experienced significant drops in revenue as a result of the ongoing Corona outbreak. This is the commercial issue that the initiative is attempting to remedy. The company has chosen to develop a careful business plan to increase its income as soon as the ongoing lockdown ends and the economy returns to a healthy state because it is finding it difficult to survive in the present market environment. The study intends to comprehend the demand for shared bicycles among the populace after the current Covid-19-related nationwide quarantine scenario ends. The model will assist management in adjusting business strategy to satisfy customer expectations and demand levels.

- What is the dataset that is being used?
The dataset being used is a sizable dataset on daily bike demand across the American market based on some parameters, including weather surveys and people's fashion preferences. The dataset includes dependent variable "cnt," which represents the total number of bike rentals, including both casual and registered ones, along with independent factors like "weathersit," "season," and "yr." The project's objective is to estimate the demand for shared bikes using the available independent variables to determine exactly how the demand varies with different features.

## Conclusions
- Season, holiday, temperature, humidity, wind speed, and other factors all have a substantial impact on the demand for shared bikes. On the test set, the model created using multiple linear regression has an R-squared score of 0.81, meaning it accounts for 81% of the variance in the target variable.
- The model can be used by management to understand how demand for shared bikes vary with different features and, in turn, to modify the business strategy to meet demand levels and satisfy customer expectations.

## Technologies Used
- Python - version 3.8.5
- Pandas - version 1.2.4
- NumPy - version 1.20.2
- Matplotlib - version 3.4.2
- Seaborn - version 0.11.1
- Scikit-learn - version 0.24.2

## Acknowledgements
This project was based on the Bike Sharing dataset provided by the consulting company contracted by BoomBikes. 
The dataset was obtained from Upgrad. The project was completed as part of an assignment for a course on machine learning.

## Contact
Created by [@JagrutiPimpale] - feel free to contact me!
