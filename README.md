📊 Black Friday Sales Analysis
📌 Overview

This project analyzes the Black Friday Sales Dataset from Kaggle, which contains transactional and demographic data of customers. The main objective is to understand customer purchasing behavior and build predictive models to estimate purchase amounts.

The dataset is widely used for Exploratory Data Analysis (EDA), Feature Engineering, and Machine Learning practice.

📂 Dataset Description

The dataset consists of two files:

train.csv → Contains ~550,000 rows with purchase amounts (target variable).

test.csv → Similar to train but without the target variable (Purchase).

📝 Columns in the dataset:
Column Name	Description
User_ID	Unique identifier for each customer
Product_ID	Unique identifier for each product
Gender	Gender of the customer (Male/Female)
Age	Age group of the customer
Occupation	Occupation code (categorical)
City_Category	City tier (A, B, C)
Stay_In_Current_City_Years	Number of years customer has stayed in current city
Marital_Status	0 = Unmarried, 1 = Married
Product_Category_1	Primary product category
Product_Category_2	Secondary product category (may have missing values)
Product_Category_3	Tertiary product category (may have missing values)
Purchase (train only)	Purchase amount (target variable)
🎯 Objectives

Perform Exploratory Data Analysis (EDA)

Understand customer demographics

Analyze purchase behavior by gender, age, city, and product categories

Conduct Feature Engineering

Handle missing values

Encode categorical variables

Create meaningful new features

Build Predictive Models

Predict purchase amount for customers in the test dataset

Generate Visual Insights

Trends in purchase behavior

Comparison across genders, age groups, and product categories

🛠️ Tech Stack

Python

Pandas, NumPy → Data manipulation

Matplotlib, Seaborn → Data visualization

Scikit-learn → Machine learning models

📊 Analyses

Average purchase by Gender & Age group

Purchase trends across Product Categories

Impact of City_Category and Stay_In_Current_City_Years on sales

Feature importance for purchase prediction

🚀 How to Run

Clone the repository

git clone https://github.com/your-username/black-friday-analysis.git
cd black-friday-analysis


Install required dependencies

pip install -r requirements.txt


Place the dataset (train.csv & test.csv) in the data/ folder.

Run the Jupyter Notebook / Python scripts to reproduce the analysis.

📈 Expected Outcomes

Insights into customer purchase behavior

Cleaned dataset ready for modeling

Predictive model to estimate Purchase Amount for test data

📌 References

Kaggle Dataset: Black Friday Sales Prediction

Seaborn & Matplotlib Documentation

Scikit-learn User Guide
