Titanic Data Mining Assignment – Documentation

1. Objective
The goal of this assignment is to perform data preprocessing, cleaning, and feature engineering on the Titanic dataset to prepare it for further analysis or modeling. The key tasks include handling missing data, extracting useful features, binning continuous variables, and combining datasets for a comprehensive view.

2. Dataset Overview
Train Dataset (train.csv): Contains 891 passenger records with information such as survival status, demographics, and ticket details.

Test Dataset (test.csv): Contains 418 passenger records for prediction, without survival labels.

3. Steps and Techniques Used
4. Data Loading
Libraries Used:

pandas for data manipulation

numpy for numerical operations

Loading CSV:

train.csv is loaded into a DataFrame df.

 Data Cleaning
 
 Missing Values
Age: Filled missing values with mean age.

Embarked: Filled missing values with mode (most frequent value).
5 . Noisy Data

6.Summary of Dataset After Preprocessing
Columns: 14 (includes new features like Title and AgeGroup)

Missing Values:

Survived is missing in test.csv.

Age, Fare, Embarked, Cabin, Title, and AgeGroup have varying degrees of missing data after the merge.

Data Types:

AgeGroup is categorical.

Survived is float64 due to NaNs.

Cabin: Dropped the Cabin column due to excessive missing data.
