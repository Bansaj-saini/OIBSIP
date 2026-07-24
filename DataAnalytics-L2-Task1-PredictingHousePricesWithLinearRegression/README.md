### House Price Prediction using Linear Regression

## Project Overview
This project focuses on predicting house prices using Linear Regression.
We used a housing dataset with features like area, bedrooms, bathrooms, and other factors to build a predictive model.

## Objective
- Build a machine learning model to predict house prices
- Perform data cleaning and exploratory data analysis (EDA)
- Evaluate model performance using standard metrics

# Tech Stack
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Steps Performed

1. Data Loading
- Imported dataset using pandas

2. Data Cleaning
- Checked for null values
- Removed missing or unnecessary data
- Converted categorical data using One-Hot Encoding

3. Exploratory Data Analysis (EDA)
- Used descriptive statistics
- Plotted correlation heatmap
- Identified important features

4. Feature Selection
- Selected features like area, bedrooms, bathrooms, parking, etc.
- Removed low-impact features

5. Model Building
- Split data into training and testing sets (80/20)
- Applied Linear Regression model

6. Model Evaluation
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

7. Visualization
- Actual vs Predicted values scatter plot
- Residual plot for error analysis

# Results
- The model was able to predict house prices with reasonable accuracy
- Features like area, number of rooms, and location had the highest impact

# Conclusion
- House prices are mainly influenced by size, rooms, and location
- Linear Regression works well for basic prediction tasks
- Further improvement can be done using advanced models

# Bonus
- Ridge and Lasso regression can be used to improve performance