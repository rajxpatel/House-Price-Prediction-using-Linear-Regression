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



  ## Histograms
<img width="1200" height="800" alt="Distribution of Numerical Variables" src="https://github.com/user-attachments/assets/c6ad2a0d-c500-456d-a2f2-9c1a023527a5" />

  ## Scatter Plots
  <img width="1500" height="1000" alt="features_plot" src="https://github.com/user-attachments/assets/80ce0ce0-b2d1-48dc-8f19-3986a35112da" />

  ## Box Plots
  <img width="2000" height="1000" alt="boxplots" src="https://github.com/user-attachments/assets/d15dcea7-1336-4029-8908-88aec8dda39a" />

  ## Correlation Matrix

<img width="1200" height="800" alt="Correlation Matrix" src="https://github.com/user-attachments/assets/c2c4d533-0334-4ad3-b4c8-11956a0286c7" />


## Residual Plot

<img width="800" height="600" alt="ResidualPlot" src="https://github.com/user-attachments/assets/55ff6d40-826b-4055-badd-754ede04a62c" />


## Actual vs Predicted Plot

<img width="800" height="600" alt="Actual_vs_Predicted" src="https://github.com/user-attachments/assets/025bdec0-04fe-44b8-b060-09f872127bc4" />


