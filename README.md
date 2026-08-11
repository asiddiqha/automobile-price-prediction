# Automobile Price Prediction

Predicting automobile prices from vehicle specifications and understanding which factors have the strongest influence on pricing.

## Overview

This project focuses on predicting the price of automobiles using their technical, physical, and categorical attributes.

The goal was not only to build a model that predicts price, but also to understand how characteristics such as engine size, horsepower, curb weight, fuel efficiency, body style, drive wheels, and make influence the final price.

I approached this as a supervised regression problem, starting with data cleaning and exploratory analysis, followed by feature engineering, model comparison, and evaluation of the final model.

## Dataset

The dataset contains automobile specifications covering:

- Vehicle make and body style
- Fuel type and aspiration
- Drive wheels and engine location
- Vehicle dimensions
- Curb weight
- Engine type and engine size
- Number of cylinders
- Horsepower
- Fuel efficiency
- Price

The dataset contains 201 records and 26 attributes. `price` is the target variable.

Missing values are represented using `?` and were handled during preprocessing.

## Problem

Given the specifications of a vehicle, can we estimate its market price?

This is a supervised regression problem because the target variable, `price`, is continuous.

Beyond prediction, the project also looks at the factors that contribute to automobile pricing and how the model can help explain pricing patterns.

## Approach

```text
Data Loading
    ↓
Data Cleaning
    ↓
Exploratory Data Analysis
    ↓
Feature Engineering
    ↓
Categorical Encoding
    ↓
Train/Test Split
    ↓
Model Training
    ↓
Cross-Validation
    ↓
Model Comparison
    ↓
Final Model Selection
    ↓
Feature Importance & Interpretation
