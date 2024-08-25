# Boba Shop Data Analysis

## Overview
This project explores the distribution and ratings of boba shops in the San Francisco Bay Area. By leveraging machine learning techniques such as K-means clustering and linear regression, the project aims to identify geographical patterns and predict boba shop ratings based on their locations. The project is intended to provide insights for potential business decisions regarding new boba shop locations.

## Project Structure
- **data/**: Contains the dataset used for the analysis.
- **notebooks/**: Jupyter Notebooks that walk through the analysis step-by-step.
- **visualizations/**: Saved visualizations generated during the analysis.
- **README.md**: Project overview and instructions.

## Analysis Techniques
### 1. K-means Clustering
- **Goal**: To identify clusters of boba shops based on their geographical locations (latitude and longitude).
- **Outcome**: Visualized clusters to understand the spatial distribution of boba shops in the area.

### 2. Linear Regression
- **Goal**: To predict boba shop ratings based on their geographical coordinates.
- **Outcome**: Evaluated the model using Mean Squared Error (MSE) and visualized the relationship between location and ratings.

### 3. Ridge Regression with Grid Search
- **Goal**: To optimize the linear regression model using Ridge Regression and GridSearchCV.
- **Outcome**: Improved model accuracy by finding the best hyperparameters.
