# customer-churn-data-analysis

# Telecom Customer Churn Analysis

This repository contains a comprehensive data analysis of telecom customer churn using Python. The main goal of this project is to identify patterns, clean structural discrepancies, and explore the underlying factors that lead customers to cancel their subscriptions.

## Project Workflow & Steps

1. **Environment Setup & Data Ingestion**:
   * Imported essential data science libraries: `pandas`, `numpy`, `matplotlib`, and `seaborn`.
   * Loaded the customer churn dataset (`Customer Churn.csv`) into a pandas DataFrame.

2. **Data Cleaning & Preprocessing**:
   * Examined structural properties and data types using `df.info()`.
   * Fixed critical missing/blank values in the `TotalCharges` column, converting it from a string to a numeric type (`float`).
   * Verified data integrity by evaluating explicit duplicates across customer records and IDs.
   * Enhanced categorical clarity by mapping binary configurations (e.g., converting the `SeniorCitizen` column from `0/1` to easier-to-understand `yes/no` labels).

3. **Exploratory Data Analysis (EDA)**:
   * Conducted initial summary statistics with `df.describe()` to understand distributions across numerical charges and tenure lengths.
   * Grouped and visualized demographic traits, contract formats, and payment methods against customer churn status.

## Core Technologies
* **Language**: Python
* **Libraries**: Pandas, NumPy, Matplotlib, Seaborn
