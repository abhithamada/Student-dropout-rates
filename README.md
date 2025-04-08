# Student-dropout-rates
# Predicting Student Dropout and Academic Success
*By Abhinanditha Thamada, Kanishca Angirish, Tayler Smith, Trishainah Varnado*

## 1. Project Scope

### 1.1 Introduction
Post-secondary education withdrawal rates significantly impacted workforce preparation (OECD, 2023). This project aimed to predict student dropout based on personal, mental, and financial health data. Using data from two datasets — one from Polytechnic University in Portugal (Martins et al., 2023) and another detailing mental health trends at various academic levels (Islam, 2023) — we created a predictive model to aid academic institutions and governments in allocating resources to reduce dropout rates.

### 1.2 Aim
The goal was to establish factors correlated with student withdrawal in higher education.

### 1.3 Purpose
By analyzing student data and trends in mental health, we aimed to predict student dropout and academic success. This data-driven model provided insights into the relationship between mental health, academic achievement, and dropout rates, helping institutions develop targeted interventions.

## 2. Methodology

### 2.1 Exploratory Data Analysis (EDA)
1. **Data Understanding**: Identified the type of data in each column and its significance.
2. **Data Cleaning**: Handled missing, duplicate, or erroneous data (imputation or removal).
3. **Feature Selection**: Selected relevant features for modeling.
4. **Data Visualization**: Visualized trends and distributions to understand data relationships.
5. **Feature Engineering**: Created new features and ensured data quality.
6. **Data Integration**: Merged the two datasets using common identifiers like student IDs.

### 2.2 Data Integration Strategies
- **Inner Join**: Merged rows with matching student IDs.
- **Left/Right Join**: Retained all records from one dataset and matched the data from the other.
- **Outer Join**: Merged all records from both datasets, filling in missing values.

### 2.3 Statistical Inference
Using machine learning classification models, we predicted student dropout based on mental health and academic data. The dataset was partitioned into training, testing, and development sets.

## 3. Deliverables
- **Database Creation**: Set up MySQL database with tables and relationships.
- **Backend Connection**: Connected the database to a Python backend to pull data.
- **Data Visualization**: Used Python and Matplotlib to visualize data trends.
- **Prediction Model**: Implemented machine learning models to predict student success and dropout.

## 4. Results
We found that students with negative experiences, particularly regarding mental health, were more likely to drop out. The model provided valuable insights into the types of support needed to help students succeed and remain enrolled.

