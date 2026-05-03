

# Titanic Data Cleaning & Preprocessing

## Problem Statement

The goal of this task is to clean and preprocess the Titanic dataset to make it suitable for data analysis and machine learning. Real-world data often contains missing values, duplicates, and inconsistent formats, so proper preprocessing is required.

## Dataset Details

The dataset is the Titanic passenger dataset in CSV format. It includes features such as passenger ID, name, age, gender, ticket class, fare, and survival status. The target variable is Survived (0 = No, 1 = Yes).

## Approach

Missing values in Age were filled using mean, and Embarked using mode. The Cabin column was removed due to excessive missing values. Duplicate records were identified and removed. Data types were standardized, and column names were converted to lowercase for consistency.

## Results

Missing values handled successfully, duplicates removed, and data types standardized. The dataset is now clean and ready for exploratory data analysis, visualization, and machine learning tasks.
