# Airbnb Price Estimator

You can find all relevant information in the repository. The detailed explanation of the work is published as a PDF in both English and Spanish.

## Abstract

This project involves data treatment and analysis from a Data Scientist's perspective to create a precise and reliable price estimator for short-term rental properties. The dataset was obtained via scraping from Airbnb, followed by data selection, cleaning, and treatment. An extensive statistical and graphical analysis was conducted to find patterns and significant correlations between property features and rental prices. Various machine learning models were evaluated to find the best-performing algorithm.

## Introduction and Background

Airbnb is a digital platform allowing individuals to list and manage short to medium-term rental accommodations. Since its inception in 2008, it has revolutionized the hospitality and tourism industry by providing an alternative to traditional hotel services. The data available from Airbnb offers a rich resource for analysis to understand the factors influencing rental prices and to develop predictive models.

## Objectives

The primary goal is to develop a machine learning model that can analyze and predict rental prices based on various factors. Key objectives include:
- Data collection and preparation from Airbnb.
- Identifying key factors that influence rental prices.
- Developing a successful machine learning model.
- Implementing an accessible estimator for users.

## Materials and Methods

The project utilizes Jupyter Notebook and various Python libraries, including Pandas, Numpy, Matplotlib, Seaborn, Scikit-learn, and Ipywidgets. The dataset was sourced from Kaggle, specifically from the "Inside Airbnb USA" dataset.

## Data Import and Initial Visualization

The dataset includes listings from five locations in the USA: Hawaii, Los Angeles, New York City, Rhode Island, and Seattle. Initial steps involve importing the data and visualizing it to understand its structure and content.

## Variable Transformation

Key transformations include:
- Converting the price from string to integer.
- Parsing and transforming amenities into numerical features.
- Converting bathroom descriptions into numerical values and categories.
- Encoding categorical variables using One-Hot Encoding.

## Data Cleaning

Outliers and irrelevant variables were removed to ensure the dataset's quality and reliability. The data was then normalized for further analysis.

## Target Setting

The target variable for the model is the rental price. The dataset was divided into predictor variables (X) and the target variable (Y).

## Graphical Analysis and Correlation

Graphical analysis, including boxplots and histograms, was conducted to visualize data distributions. Pearson correlation was used to identify relationships between variables.

## Machine Learning Models

Various machine learning models were evaluated, including:
- Linear Regression
- Ridge Regression
- Lasso Regression
- Decision Tree
- Random Forest
- Gradient Boosting

The models were trained and tested to identify the best-performing algorithm based on Mean Squared Error (MSE) and R² scores.

## Price Estimator

The final estimator integrates the best-performing model with a user-friendly interface, allowing users to input property features and obtain rental price predictions easily.

## Conclusions

The project demonstrates the utility of machine learning techniques in the real estate market, providing a valuable tool for potential landlords and tenants to estimate rental prices accurately.
