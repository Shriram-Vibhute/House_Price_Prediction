# House Price Prediction - Machine Learning Project 🏡💹💸

Welcome to the My House Price Prediction project! This repository contains code and resources for predicting house prices using machine learning techniques. The project involves multiple stages, from data exploration and preprocessing to building and evaluating machine learning models.

![image](https://github.com/user-attachments/assets/153fdc59-af6d-4513-a83f-a6e51cdac25a)

## Table of Contents

- [Introduction](#introduction)
- [Dataset Overview](#dataset-overview)
- [Data Visualization](#data-visualization)
- [Data Preprocessing](#data-preprocessing)
- [Feature Engineering](#feature-engineering)
- [Feature Transformation](#feature-transformation)
- [Machine Learning Pipelines](#machine-learning-pipelines)
- [Data Sampling](#data-sampling)
- [Model Selection, Training, and Validation](#model-selection-training-and-validation)

## Introduction

This project aims to predict house prices using historical data. By applying various machine learning techniques, the goal is to build a model that can accurately estimate house prices based on features such as location, size, and amenities. The project follows a systematic approach, including data visualization, preprocessing, feature engineering, and model evaluation.

## Dataset Overview

The dataset used in this project contains detailed information about houses, including:

- **longitude**: The longitude of the house's location. It indicates the geographic location of the house in terms of east or west position relative to the Prime Meridian.

- **latitude**: The latitude of the house's location. It represents the north or south position relative to the Equator.

- **housing_median_age**: The median age of the houses in the block. This attribute gives an idea of how old the houses are on average in that area.

- **total_rooms**: The total number of rooms in the house. This includes all rooms such as bedrooms, bathrooms, living rooms, etc.

- **total_bedrooms**: The total number of bedrooms in the house. This attribute provides information on how many bedrooms are in the house.

- **population**: The total number of people residing in the block. This is a measure of the population density of the area.

- **households**: The number of households in the block. A household typically refers to a group of people living together in a single dwelling.

- **median_income**: The median income of households in the block, - expressed in tens of thousands of dollars. This is a key economic indicator for the area.

- **median_house_value**: The median house value in the block, expressed in dollars. This is the target variable for predicting house prices in many machine learning models.

- **ocean_proximity**: This categorical attribute indicates the proximity of the house to the ocean. Possible values include categories like "NEAR BAY," "NEAR OCEAN," "ISLAND," "INLAND," and "OUTLYING."

The dataset is split into training and testing subsets for model evaluation.

## Data Visualization

Data visualization helps understand the distribution and relationships within the dataset. This step includes:

- **Histograms**: To visualize the distribution of numerical features like size and price.
- **Scatter Plots**: To explore relationships between features, such as the correlation between size and price.
- **Box Plots**: To detect outliers and visualize the spread of features like price across different categories.
- **Heatmaps**: For showing the correlation between each features in the dataset

Visualization code examples can be found in the `visualization` directory.

## Data Preprocessing

Data preprocessing involves preparing the dataset for analysis and model training. This includes:

- **Handling Missing Values**: Identifying and filling or removing missing data.
- **Outlier Detection**: Identifying outliers and removing them using IsolationTrees

Preprocessing scripts are available in the `preprocessing` directory.

## Feature Engineering

Feature engineering involves creating new features or modifying existing ones to improve model performance. Techniques used include:

- **Creating Interaction Features**: Combining existing features to capture interactions.
- **Polynomial Features**: Adding polynomial terms to capture non-linear relationships. (soon)

Feature engineering scripts can be found in the `feature_engineering` directory.

## Feature Transformation

Feature transformation focuses on applying mathematical transformations to features to enhance model performance. This includes:

- **Log Transformation**: To handle skewed distributions.
- **Standardization**: To ensure features have a mean of zero and a standard deviation of one.
- **One Hot Encoding**: Converting categorical features into numerical values.

Transformation scripts are located in the `feature_transformation` directory.

## Machine Learning Pipelines

Machine learning pipelines streamline the process of training and evaluating models. Pipelines ensure that all preprocessing, feature engineering, and model training steps are executed in a consistent order. The pipeline setup includes:

- **Pipeline Creation**: Combining preprocessing, feature engineering, and model training into a single workflow.

Pipeline code is available in the `pipelines` directory.

## Data Sampling

Data sampling techniques are used to balance the dataset and ensure a representative sample for training and evaluation. This includes:

- **Stratified Sampling**: Ensuring that each sample represents the overall dataset distribution.

Sampling scripts are found in the `sampling` directory.

## Model Selection, Training, and Validation

The final stage involves selecting and training machine learning models, and validating their performance. This includes:

- **Model Selection**: Choosing models such as Linear Regression, Decision Trees, or Random Forests based on performance criteria.
- **Training**: Fitting models to the training data.
- **Validation**: Evaluating model performance using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared.
- **Cross-Validation**: Splitting the data into multiple folds to assess model performance.
- **Hyperparameter Tuning**: Optimizing model parameters using techniques such as GridSearchCV.

Model training and validation code is available in the `modeling` directory.

---

Feel free to adjust any sections or add more details based on your project's specifics. PEACE OUT.✌️