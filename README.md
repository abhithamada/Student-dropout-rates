# Student-dropout-rates
# Predicting Student Dropout and Academic Success
*By Abhinanditha Thamada, Kanishca Angirish, Tayler Smith, Trishainah Varnado*

## 1. Project Scope

### 1.1 Introduction
Post-secondary education withdrawal rates significantly impact workforce preparation (OECD, 2023). This project aims to predict student dropout based on personal, mental, and financial health data. Using data from two datasets — one from Polytechnic University in Portugal (Martins et al., 2023) and another detailing mental health trends at various academic levels (Islam, 2023) — we will create a predictive model to aid academic institutions and governments in allocating resources to reduce dropout rates.

### 1.2 Aim
To establish factors correlated with student withdrawal in higher education.

### 1.3 Purpose
By analyzing student data and trends in mental health, we aim to predict student dropout and academic success. This data-driven model will provide insights into the relationship between mental health, academic achievement, and dropout rates, helping institutions develop targeted interventions.

## 2. Methodology

### 2.1 Exploratory Data Analysis (EDA)
1. **Data Understanding**: Identify the type of data in each column and its significance.
2. **Data Cleaning**: Handle missing, duplicate, or erroneous data (imputation or removal).
3. **Feature Selection**: Select relevant features for modeling.
4. **Data Visualization**: Visualize trends and distributions to understand data relationships.
5. **Feature Engineering**: Create new features and ensure data quality.
6. **Data Integration**: Merge the two datasets using common identifiers like student IDs.

### 2.2 Data Integration Strategies
- **Inner Join**: Merge rows with matching student IDs.
- **Left/Right Join**: Retain all records from one dataset and match the data from the other.
- **Outer Join**: Merge all records from both datasets, filling in missing values.

### 2.3 Statistical Inference
Using machine learning classification models, we will predict student dropout based on mental health and academic data. The dataset will be partitioned into training, testing, and development sets.

## 3. Deliverables
- **Database Creation**: Set up MySQL database with tables and relationships.
- **Backend Connection**: Connect the database to a Python backend to pull data.
- **Data Visualization**: Use Python and Matplotlib to visualize data trends.
- **Prediction Model**: Implement machine learning models to predict student success and dropout.

## 4. Results
We expect that students with negative experiences, particularly regarding mental health, are more likely to drop out. The model will provide valuable insights into the types of support needed to help students succeed and remain enrolled.
