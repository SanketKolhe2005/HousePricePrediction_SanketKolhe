# House Price Prediction Using Machine Learning

## Overview

This project was completed as part of the Machine Learning Internship at XYlofy. The objective was to develop a predictive model capable of estimating house prices using property-related features such as area, number of rooms, parking availability, furnishing status, and other housing attributes.

The project covers the complete machine learning workflow, including data exploration, preprocessing, visualization, model development, performance evaluation, and result interpretation.

## Dataset Description

The dataset contains information about residential properties and their market prices. Various numerical and categorical features were used to understand the factors affecting house valuation.

**Target Variable**

* Price

**Input Features**

* Area
* Bedrooms
* Bathrooms
* Stories
* Main Road Access
* Guest Room
* Basement
* Hot Water Heating
* Air Conditioning
* Parking
* Preferred Area
* Furnishing Status

## Methodology

### Data Exploration

The dataset was inspected to understand its structure, dimensions, and feature distribution. Missing values and duplicate records were checked before proceeding with analysis.

### Data Preparation

Categorical variables were transformed into numerical representations using one-hot encoding. The processed dataset was then divided into training and testing sets.

### Model Training

Two regression algorithms were implemented:

* Linear Regression
* Random Forest Regressor

### Model Evaluation

The models were assessed using:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

## Results

### Linear Regression

* MAE: 970,043
* RMSE: 1,324,507
* R² Score: 0.653

### Random Forest Regressor

* MAE: 1,021,546
* RMSE: 1,400,566
* R² Score: 0.612

### Best Model

Linear Regression achieved the strongest overall performance and provided more accurate predictions on the test dataset.

## Key Findings

* Property area was one of the most influential factors affecting house prices.
* Houses with additional bathrooms and parking facilities generally had higher values.
* Amenities such as air conditioning and preferred location positively impacted pricing.
* Linear Regression captured the relationship between housing features and price more effectively than Random Forest for this dataset.

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook

## Conclusion

The project successfully demonstrated how machine learning can be applied to real estate valuation. Through data analysis and predictive modeling, valuable insights were obtained regarding the factors that influence housing prices. The final model can serve as a foundation for developing more advanced property valuation systems in the future.

## Author

Sanket Kolhe

Machine Learning Internship Project

**XYlofy**
