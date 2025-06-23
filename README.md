# Titanic Dataset - Data Cleaning & Preprocessing 

##  Task Overview

This project focuses on **cleaning and preprocessing** the Titanic dataset to prepare it for machine learning tasks. It demonstrates essential steps like handling missing values, encoding categorical variables, scaling numerical features, and identifying/removing outliers.

---

##  Tools & Libraries Used

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **scikit-learn**

---

##  Dataset

- Dataset used: Titanic dataset 
- [Download Titanic Dataset](https://www.kaggle.com/competitions/titanic/data) 

---

##  Steps Performed

### 1. **Exploratory Data Analysis**
- Loaded dataset using Pandas
- Viewed summary statistics and data types
- Checked for missing values

### 2. **Missing Value Handling**
- Filled missing `Age` values with median
- Filled missing `Embarked` values with mode
- Dropped `Cabin` column due to excessive missing values

### 3. **Categorical Encoding**
- Converted `Sex` column to numerical (0 = male, 1 = female)
- One-hot encoded the `Embarked` column

### 4. **Feature Scaling**
- Standardized numerical columns `Age` and `Fare` using `StandardScaler`

### 5. **Outlier Detection and Removal**
- Used boxplots to visualize outliers in `Age` and `Fare`
- Removed outliers in `Fare` using IQR method

---

##  Repository Contents
- Data Cleaning & Preprocessing.ipynb
- titanic_cleaned.csv
- Titanic-Dataset.csv
