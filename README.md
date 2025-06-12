# Task 1: Data Preprocessing Pipeline (ETL)

## ✅ Objective
Build a pipeline for Extracting, Transforming, and Loading data using Pandas and Scikit-learn.

## 📊 Dataset
Titanic Dataset (loaded from [this link](https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv))

## 🛠️ Steps Performed
- Loaded and explored the dataset
- Dropped irrelevant features (`PassengerId`, `Name`, `Ticket`, `Cabin`)
- Handled missing values (mean for Age, mode for Embarked)
- Encoded categorical features (`Sex`, `Embarked`)
- Scaled numerical data with `StandardScaler`
- Split into train and test sets
- Saved processed data

## 📁 Files
- `titanic_etl_pipeline.ipynb`: Code and explanation
- `X_train.csv`, `X_test.csv`, etc.: Transformed datasets (optional)

## ✅ Tools Used
- Python
- Pandas
- Scikit-learn
