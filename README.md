# 🚢 Titanic Dataset - Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project is a part of the **Data Science with Python Internship – Task 3**. The objective is to perform a Mini Exploratory Data Analysis (EDA) on the Titanic dataset by cleaning the data, handling missing values, engineering new features, and creating meaningful visualizations to uncover survival patterns.

## 🎯 Objectives

* Clean and preprocess the dataset
* Handle missing values using appropriate techniques
* Perform exploratory data analysis (EDA)
* Engineer new features for deeper insights
* Visualize relationships between important variables
* Summarize findings through data storytelling

## 📂 Dataset

* **Dataset:** Titanic-Dataset.csv
* **Records:** 891 passengers
* **Target Variable:** `Survived`

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

## 🧹 Data Preprocessing

The following preprocessing steps were performed:

* Filled missing values in the **Age** column using the mean
* Filled missing values in the **Embarked** column using the mode
* Removed the **Cabin** column due to a high percentage of missing values
* Created a **Family Size** feature from `SibSp` and `Parch`
* Grouped passengers into different **Age Groups**

## 📊 Exploratory Data Analysis

The analysis includes:

* Survival Rate by Age Group
* Survival Rate by Embarkation Port
* Survival Rate by Family Size

## 📈 Visualizations

The notebook contains the following visualizations:

* Age Distribution Histogram
* Correlation Heatmap
* Survival Rate by Family Size
* Survival Rate by Age Group
* Survival Rate by Embarkation Port
* Survival Count
* Survival by Gender

## 🔍 Key Insights

* Young adults formed the largest group of passengers.
* Female passengers had significantly higher survival rates than males.
* Passenger class had a strong influence on survival.
* Smaller families generally experienced better survival rates.
* Fare showed a positive relationship with survival.
* Embarkation port also influenced survival probability.

## 📚 Learning Outcomes

This project demonstrates practical skills in:

* Data Cleaning
* Missing Value Imputation
* Feature Engineering
* Exploratory Data Analysis (EDA)
* Data Visualization
* Statistical Interpretation
* Data Storytelling

## 📌 Conclusion

The exploratory analysis reveals several factors that influenced passenger survival on the Titanic, including age, gender, passenger class, family size, fare, and embarkation port. This project highlights how effective data preprocessing and visualization can transform raw data into meaningful insights and provides a strong foundation for future predictive modeling tasks.

Author: Raghav Garg Internship Task: Data Analysis with Python – Task 3
