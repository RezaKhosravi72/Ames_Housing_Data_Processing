# Ames Housing Data Processing

## Overview

This project aimed to clean, preprocess, analyze and model housing price data from the Ames Housing Dataset to help gain insights and build a linear regression model for price prediction.

## Data

The dataset contained residential home sales data from 2006 to 2010 for Ames, Iowa. It included around 80 explanatory variables describing aspects of each home such as quality, size, condition, location and sale prices. 

## Goal

The main goals were to:

  1. Perform data cleaning and preprocessing such as outlier removal, imputation of missing values and encoding of categorical variables.

  2. Explore and visualize trends in the data to understand factor relationships. 

  3. Develop and evaluate a linear regression model to predict house sale prices based on property attributes.

## Methodology

The steps undertaken were:

  1. Data loading and exploration to understand distributions, outliers, missing values etc. 
  
  2. Outlier removal by subject matter knowledge and statistical analysis. 
  
  3. Imputation of missing data using mode/mean depending on variable type.
  
  4. Encoding of categorical variables as binary dummy variables. 
  
  5. Train/test split of preprocessed dataframe.
  
  6. Linear regression model fitting and evaluation on training set using R^2 and RMSE. 
  
  7. Prediction and evaluation on test set to gauge generalization.
  
  8. Analysis of variable importance to determine key driving factors.
  
  9. Refinement of preprocessing and model building based on evaluation metrics.

## Outcomes

The project yielded:

- A clean and preprocessed dataframe with 80 variables and 1500+ observations.

- Visual insights into relationships between variables and sale price.

- A linear regression model with R^2=0.88 and RMSE=30k on test set for price prediction. 

- Determination of most important attributes correlated with property value.


The findings provided homeowners and realtors valuable data-driven insights to assess property prices. Future work may involve deeper explorations and more advanced techniques.
