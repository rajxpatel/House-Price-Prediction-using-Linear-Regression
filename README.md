# House Price Prediction using Multiple Linear Regression

##  Project Overview

This project develops a Multiple Linear Regression model to predict house prices based on various housing characteristics. The project follows a complete machine learning workflow including data exploration, preprocessing, model development, evaluation, and statistical diagnostics.

The objective is not only to build a predictive model but also to understand how different housing features influence house prices through statistical analysis.

---

## Objectives

- Perform Exploratory Data Analysis (EDA)
- Analyze the distribution of housing variables
- Detect outliers using boxplots
- Study relationships between variables
- Encode categorical variables
- Build a Multiple Linear Regression model
- Evaluate model performance
- Interpret regression coefficients
- Validate statistical significance using OLS
- Check multicollinearity using Variance Inflation Factor (VIF)

---

## Dataset Information

The dataset contains **545 residential houses** with **13 variables**.

### Features

- Area
- Bedrooms
- Bathrooms
- Stories
- Main Road
- Guest Room
- Basement
- Hot Water Heating
- Air Conditioning
- Parking
- Preferred Area
- Furnishing Status

### Target Variable

- House Price

---

##  Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Statsmodels

---

## 🔍 Exploratory Data Analysis

The following analyses were performed:

- Distribution plots
- Scatter plots
- Box plots
- Correlation Matrix
- Feature relationship analysis

---

##  Data Preprocessing

- Checked missing values
- Converted categorical variables using One-Hot Encoding
- Split dataset into training and testing sets (80:20)

---

## Model Used

**Multiple Linear Regression**

The model was trained using Scikit-learn's `LinearRegression()`.

---

## Model Performance

| Metric | Value |
|---------|--------|
| MAE | 970,043 |
| RMSE | 1,324,507 |
| R² Score | 0.653 |

The model explains approximately **65%** of the variation in house prices on the test dataset.

---

## Statistical Analysis (OLS Regression)

OLS regression was performed using the Statsmodels library.

### Results

- R² = 0.686
- Adjusted R² = 0.676
- F-statistic = 70.90
- Model p-value < 0.001

### Significant Variables

- Area
- Bathrooms
- Stories
- Parking
- Main Road
- Basement
- Hot Water Heating
- Air Conditioning
- Preferred Area
- Furnishing Status (Unfurnished)

---

## Model Diagnostics

The following diagnostic analyses were performed:

- Residual Plot
- Actual vs Predicted Plot
- Variance Inflation Factor (VIF)

### Multicollinearity

All predictor variables have VIF values below **2**, indicating that multicollinearity is not a concern.

---

## Visualizations

The project includes:

- Histograms
- Scatter Plots
- Box Plots
- Correlation Heatmap
- Residual Plot
- Actual vs Predicted Plot

  ## Correlation Matrix

![Correlation Matrix](images/correlation.png)

## Residual Plot

![Residual Plot](images/residual_plot.png)

## Actual vs Predicted Plot

![Actual vs Predicted](images/actual_vs_predicted.png)



## ⭐ If you found this project useful, consider giving it a star.
