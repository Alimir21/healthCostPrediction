# Healthcare Cost Prediction with Neural Networks

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange)
![License](https://img.shields.io/badge/License-MIT-green)

A regression model that predicts individual medical costs billed by health insurance using personal characteristics like age, BMI, smoking status, etc.

## Project Overview

This project uses a deep neural network to predict healthcare expenses based on:
- Demographic factors (age, sex)
- Health metrics (BMI, children)
- Lifestyle choices (smoking status)
- Geographic region

The model achieves **Mean Absolute Error (MAE) under $3,500**, meaning it can predict healthcare costs within this margin of error.

## Key Features

- Data preprocessing pipeline for categorical variables
- Customizable neural network architecture
- Model evaluation metrics (MAE, MSE)
- Visualization of predictions vs actual values
- Complete training history tracking

## Dataset

The dataset contains 1,338 records with 7 features:

| Feature    | Description                     | Type        |
|------------|---------------------------------|-------------|
| age        | Age of primary beneficiary      | Numerical   |
| sex        | Gender (male/female)            | Categorical |
| bmi        | Body Mass Index                | Numerical   |
| children   | Number of dependents           | Numerical   |
| smoker     | Smoking status                 | Categorical |
| region     | Geographic region              | Categorical |
| expenses   | Individual medical costs (target) | Numerical   |
