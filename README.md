
#  Car Price Prediction
 ## Project Overview
The car's price can be affected by multiple factors such as engine characteristics, car dimensions, fuel type, and others. To predict the car's price, we need to identify which features are more relevant and use them to obtain a more accurate predicted price. Using Python libraries, we explore various factors and car characteristics. Then, we apply multiple techniques to select the most important features and achieve a satisfactory result. 


## Dataset: 
The dataset contains 205 rows and 23 columns representing different features of cars, divided into numerical and categorical values.

[Dataset Link](https://www.kaggle.com/datasets/hellbuoy/car-price-prediction)

## Methodology
We begin by exploring the dataset to familiarize ourselves with its structure and verify data quality, checking for missing values, duplicates, and other inconsistencies. Next, we analyze the most relevant features for car price prediction. We apply multiple techniques for predicting car prices, including Linear Regression, Ridge Regression, Lasso Regression, and Principal Component Analysis (PCA).

## Results 
| Model                          | R² Score  | MSE   |
|---------------------------------------|-----------|-------|
| Linear Regression (feature selection) | 81.86%   | 0.225 |
| Ridge Regression (feature selection)  | 81.76%   | 0.226 |
| Ridge Regression (all features)       | 83.11%   | 0.209 |
| Lasso Regression                      | 83.08%   | 0.210 |
| PCA & Linear Regression               | 84.5%    | 0.192 |


**Author:**  
- Souhaila El Kadaoui  






