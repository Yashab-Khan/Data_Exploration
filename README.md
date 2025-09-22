# Data_Exploration

Data exploration step of AIML project using Titanic dataset

# Task 1: Data Cleaning & Preprocessing

## Objective
Learn how to clean and prepare raw data for Machine Learning using Python.

## Dataset
- Titanic dataset from Seaborn library (`sns.load_dataset("titanic")`)
- No external CSV required

## Tools & Libraries
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- scikit-learn (SimpleImputer, LabelEncoder, StandardScaler)

## Steps Performed
1. Data Exploration
   - Checked first few rows, data types, missing values
2. Handling Missing Values
   - Numerical: filled with median
   - Categorical: filled with most frequent value
3. Encoding Categorical Features
   - Used `LabelEncoder` to convert categorical features into numeric
4. Feature Scaling**
   - Standardized numerical features using `StandardScaler`
5. Outlier Detection & Removal
   - Visualized with boxplots
   - Removed outliers using IQR method
6. Final Dataset
   - Cleaned, ready for Machine Learning

