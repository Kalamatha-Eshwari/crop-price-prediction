# Crop Price Prediction Project

## Project Overview

This project aims to predict crop prices based on a comprehensive dataset containing agricultural and environmental factors. The dataset encompasses cultivation costs, production metrics, weather conditions, and crop types across various states.

## Project Scope

### 1. Data Loading and Exploration

- **Dataset Loading:** Loaded the `crop_price.csv` dataset using pandas for initial exploration.
- **Data Quality Check:** Ensured data integrity by checking for duplicates and missing values.
- **Data Distribution Analysis:** Utilized histograms to visualize the distribution of features and identify initial patterns.

### 2. Data Preprocessing and Transformation

- **Handling Skewed Data:** Applied logarithmic transformations to mitigate skewness in numerical columns such as cultivation costs and production metrics.
- **Categorical Encoding:** Engineered dummy variables for categorical features like states and crop types to prepare them for modeling.

### 3. Feature Engineering

- **Feature Creation:** Introduced new features, including the average of logarithmic transformations of related variables, to capture additional insights from the data.

### 4. Modeling

- **Regression Models Implemented:**
  - **Linear Regression**
  - **SVR (Support Vector Regression)**
  - **Decision Tree Regression**
- **Model Training:** Trained each regression model to predict crop prices based on the transformed dataset.

### 5. Model Evaluation

- **Performance Metrics Used:**
  - **Mean Squared Error (MSE)**: Evaluated model accuracy by calculating the MSE between predicted and actual crop prices.
  - **R^2 Score**: Assessed the goodness of fit of each model, indicating how well the models explain the variability in crop prices.

### 6. Data Visualization

- **Insightful Plots:** Leveraged scatter plots, box plots, and histograms to visualize relationships between features, identify outliers, and understand data distributions pre and post-transformation.

## Key Learnings

- **Data Manipulation:** Gained proficiency in loading, cleaning, and transforming datasets for machine learning projects.
- **Feature Engineering Techniques:** Learned strategies to enhance model performance by creating and transforming features.
- **Regression Modeling:** Implemented and evaluated multiple regression algorithms to predict crop prices effectively.
- **Model Evaluation:** Understood the importance of MSE and R^2 score in assessing model performance and suitability for real-world applications.
- **Data Visualization:** Utilized matplotlib and seaborn libraries for visualizing data patterns and relationships, crucial for deriving actionable insights.

This project provided practical experience in data preprocessing, feature engineering, regression modeling, and evaluation, essential for leveraging machine learning in agricultural price forecasting.

