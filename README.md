# Data Leverager - Power Query Transformation Project

## Project Overview
This project focuses on data cleaning, transformation, integration, and preparation using Power BI Power Query. The goal is to perform ETL operations without using dashboards or DAX.

## Objectives
- Data Cleaning
- Data Transformation
- Data Integration
- Data Preparation using Power Query

## Dataset Used
The following datasets were used in this project:

- Sales_Jan.xlsx
- Sales_Feb.xlsx
- Sales_Mar.xlsx
- Employee_Data.xlsx

Total Sales Records: 200 Rows

## Transformations Performed

### 1. Data Extraction
- Imported Excel files
- Combined monthly sales data

### 2. Data Cleaning
- Removed blank rows
- Removed duplicates
- Changed data types

### 3. Text Tools
- TRIM
- CLEAN

### 4. Numeric Tools
- Profit Column = Revenue - Cost

### 5. Date & Time Tools
- Year Extraction
- Month Extraction
- Quarter Extraction

### 6. Conditional Column
Created Sales Category:
- High (>=10000)
- Medium (5000–9999)
- Low (<5000)

### 7. Merge & Append
- Appended Jan, Feb, Mar files
- Merged Employee data using EmployeeID

### 8. Grouping & Aggregation
- Region-wise Total Sales

## Files Included
- Power BI (.pbix)
- Dataset files
- Screenshots
- Project Report
