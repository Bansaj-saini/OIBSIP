### Objective

The objective of this project is to clean a messy dataset and transform it into a structured, analysis-ready dataset by handling missing values, duplicates, inconsistent formats, and outliers.

# Tech Stack
- Python
- Pandas
- NumPy
- Jupyter Notebook

# Dataset Used
- Titanic Dataset
- Contains passenger details like Age, Fare, Cabin, Embarked, etc.

## Data Cleaning Steps Performed

# Data Quality Check
- Checked dataset shape
- Identified missing values
- Found duplicate rows
- Reviewed data types

# Missing Value Handling
- Age → Filled with median
- Embarked → Filled with mode
- Cabin → Dropped (too many missing values)

# Duplicate Removal
- Removed duplicate rows from dataset

# Data Standardization
- Converted text data (e.g., gender) to lowercase
- Removed extra spaces from column names

# Outlier Detection
- Used IQR (Interquartile Range) method
- Removed extreme values from numerical columns

# Data Type Correction
- Converted Age & Fare → float
- Converted PassengerId → string

# Final Output
- Cleaned dataset saved as: cleaned_titanic.csv

# Key Learnings
- Handling missing data using different strategies
- Data cleaning using Pandas
- Working with real-world messy datasets
- Outlier detection using IQR method

## Conclusion
- The dataset has been successfully cleaned and is now ready for data analysis and visualization.