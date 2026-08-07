# Customer Churn Analysis & Prediction

## Project Overview

This project is an end-to-end Customer Churn Analysis and Prediction project developed using SQL Server, Power BI, Python, and Machine Learning.

The objective is to analyze customer behavior, identify factors associated with customer churn, build an interactive Power BI dashboard, and predict customers who are likely to churn using a Random Forest machine learning model.

## Tools & Technologies

- SQL Server
- Power BI
- Python
- Pandas
- Scikit-learn
- Random Forest
- Excel
- DAX

## Project Workflow

Raw Customer Data
        ↓
SQL Server – Data Cleaning & ETL
        ↓
Power BI – Exploratory & Interactive Analysis
        ↓
Python – Machine Learning
        ↓
Random Forest Model
        ↓
Predicted Churners
        ↓
Power BI – Prediction Analysis

## Project Components

### 1. SQL Server

SQL Server was used for data preparation, cleaning, transformation, and customer churn analysis.

Key activities include:

- Data cleaning
- Data transformation
- Customer segmentation
- Churn analysis
- Aggregation and filtering
- Preparing data for Power BI and Machine Learning

### 2. Power BI Dashboard

An interactive Power BI dashboard was developed to analyze customer churn and customer characteristics.

The dashboard includes analysis of:

- Customer churn
- Gender
- Age groups
- Customer tenure
- Monthly charges
- Total revenue
- Number of referrals
- Churn reasons
- Customer behavior

### 3. Machine Learning

Python and Scikit-learn were used to develop a Random Forest model for predicting customer churn.

The model uses customer attributes to identify customers who are likely to churn.

### 4. Prediction Results

The machine learning prediction generated:

**378 predicted churners**

These predicted customers were imported into Power BI for further analysis and visualization.

## Key Skills Demonstrated

- SQL
- SQL Server
- Data Cleaning
- ETL
- Power BI
- DAX
- Data Visualization
- Python
- Pandas
- Scikit-learn
- Random Forest
- Machine Learning


## Repository Structure

```text
Customer-Churn-Analysis/
│
├── README.md
│
├── PowerBI/
│   └── Customer_Churn_Analysis.pbix
│
├── Python/
│   └── churn_prediction.py
│
├── SQL/
│   └── churn_analysis.sql
│
├── Excel/
   └── Prediction_Data.xlsx
