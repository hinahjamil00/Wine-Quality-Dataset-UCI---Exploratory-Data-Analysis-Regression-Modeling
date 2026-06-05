# Wine-Quality-Dataset-UCI---Exploratory-Data-Analysis-Regression-Modeling
This project performs Exploratory Data Analysis (EDA), Feature Engineering, and Machine Learning modeling on the Wine Quality dataset from the UCI Machine Learning Repository. The goal is to predict wine quality scores using physicochemical properties of red and white wines using regression techniques.

## Dataset Overview

The Wine Quality dataset contains physicochemical and sensory data for Portuguese Vinho Verde wines.

- Source: UCI Machine Learning Repository
- Total Samples: 4,898
- Features: 11 input variables + 1 target variable
- Problem Type: Regression (can also be used for classification)

## Features
Physicochemical properties include:
- fixed acidity
- volatile acidity
- citric acid
- residual sugar
- chlorides
- free sulfur dioxide
- total sulfur dioxide
- density
- pH
- sulphates
- alcohol

## Target Variable
- quality (score between 0 and 10)

## Objective
To predict wine quality based on chemical properties and understand which features influence wine quality the most.

## Key Challenges
- Imbalanced target distribution (most wines are average quality)
- Feature correlation (e.g., alcohol vs density)
- Presence of outliers in sulfur dioxide and residual sugar
