
# Linear Regression on the California Housing Dataset

### AI/ML Laboratory – CSET301 (Lab 04)

## Overview

This project implements a simple linear regression model using the California Housing dataset.
The purpose of the lab is to understand how to load datasets, perform preprocessing and exploratory data analysis, train a regression model, evaluate performance metrics, and visually analyze prediction behavior.

## Objectives

* Load and explore a real-world dataset.
* Perform EDA to understand variable distributions and correlations.
* Select meaningful numerical features for regression.
* Train a linear regression model using scikit-learn.
* Evaluate model performance using R² score and Mean Squared Error.
* Visualize predicted vs actual values.
* Interpret results and discuss model limitations.

## Dataset

The dataset used is the California Housing dataset available through scikit-learn.

Reference:
[https://scikit-learn.org/stable/modules/generated/sklearn.datasets.fetch_california_housing.html](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.fetch_california_housing.html)

The dataset contains the following numerical attributes:

* MedInc: Median income
* HouseAge: Median house age
* AveRooms: Average number of rooms per household
* AveBedrms: Average number of bedrooms per household
* Population: Block group population
* AveOccup: Average number of occupants per household
* Latitude: Location latitude
* Longitude: Location longitude
* MedHouseValue: Target variable (median home value)

## Steps Implemented

### 1. Data Loading

* The California Housing dataset is loaded using the `fetch_california_housing()` function from scikit-learn.
* The dataset is converted into a Pandas DataFrame to simplify analysis and manipulation.

### 2. Exploratory Data Analysis (EDA)

* Summary statistics and distribution plots are generated for key variables.
* A correlation heatmap is constructed to identify relationships between features and the target variable.

### 3. Feature Selection

A subset of relevant numerical features is selected to build the regression model.
Commonly used features include:

* MedInc
* AveRooms
* AveOccup
* HouseAge

### 4. Train-Test Split

* The dataset is divided into training (80 percent) and testing (20 percent) sets using `train_test_split()`.

### 5. Model Training

* A `LinearRegression` model from scikit-learn is initialized and trained on the selected features.

### 6. Model Evaluation

Evaluation metrics include:

* R² Score: Measures variance explained by the model.
* Mean Squared Error (MSE): Measures average prediction error.

### 7. Visualization

A scatter plot of actual vs predicted median house values is generated to visually assess model performance.

### 8. Interpretation

Key observations include:

* Strengths and weaknesses of linear regression.
* Impact of linearity assumptions.
* Influence of outliers and feature correlations.
* Potential improvements using advanced models such as Random Forest or Gradient Boosting.

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* scikit-learn

## How to Run

1. Clone the repository.
2. Install dependencies:

   ```
   pip install numpy pandas matplotlib seaborn scikit-learn
   ```
3. Run the notebook or Python script containing the implementation.

## Files in This Repository

* `linear_regression_california.ipynb`
  Jupyter notebook with complete code and visualizations.
* `README.md`
  Project documentation and lab summary.

## Conclusion

This lab provides hands-on practice with building and evaluating a linear regression model on a real dataset. The exercise reinforces concepts of feature selection, EDA, model evaluation, and interpretation of results, forming a foundation for more complex machine learning techniques.

---
