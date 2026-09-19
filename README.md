# House Price Prediction

## Project Overview

This project explored factors associated with house prices and compared two machine-learning models for predicting property prices.

Using Python, I conducted exploratory data analysis before developing and evaluating models using Multiple Linear Regression and Random Forest Regression.

## Dataset

The dataset included the following property characteristics:

- Square feet
- Number of bedrooms
- Number of bathrooms
- Number of floors
- Garage size
- Location score
- Distance to the city centre
- House price

## Tools & Technologies

- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Microsoft Fabric

## Exploratory Data Analysis

An exploratory analysis was conducted to understand the distribution of house prices and the relationships among the variables.

The analysis included:

- Descriptive statistics
- Distribution of house prices
- Scatter plots
- Correlation analysis
- Correlation heatmap

Square feet and number of bedrooms showed some of the stronger positive relationships with house price in the dataset.

## Predictive Modelling

Two regression models were developed:

### Multiple Linear Regression

The dataset was divided into training and testing data. A Multiple Linear Regression model was trained using the property characteristics as predictor variables.

**Test RMSE: approximately 63,952.38**

### Random Forest Regression

A Random Forest Regression model with 100 trees was trained using the same training and testing data.

**Test RMSE: approximately 71,733.36**

## Model Comparison

Multiple Linear Regression produced the lower RMSE on the test data.

| Model | Test RMSE |
|---|---:|
| Multiple Linear Regression | 63,952.38 |
| Random Forest Regression | 71,733.36 |

For this dataset and train/test split, the Multiple Linear Regression model therefore produced predictions closer to the actual house prices than the Random Forest model.

This comparison also demonstrated why model performance should be evaluated using test data rather than assuming that a more complex model will necessarily perform better.

## Skills Demonstrated

This project demonstrates my ability to:

- Prepare and explore data using Python and Pandas
- Conduct exploratory data analysis
- Visualise relationships within data
- Interpret correlation
- Prepare predictor and target variables
- Split data into training and testing datasets
- Build Multiple Linear Regression and Random Forest Regression models
- Generate predictions
- Evaluate regression models using RMSE
- Compare model performance and communicate findings

## Potential Improvements

Future analysis could explore:

- Additional property characteristics
- A larger dataset
- Feature engineering
- Adjustment of model parameters
- Further comparison of predictive models

## Repository Files

- `House_Price_Prediction.ipynb` – analysis and predictive modelling notebook
