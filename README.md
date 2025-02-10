# Databel Churn Analysis (MS Excel 365)

## Overview
This project provides a churn analysis solution using Microsoft Excel 365 for a telecom company, Databel. It focuses on analyzing customer retention data to identify churn patterns and predict the likelihood of customers leaving the business. The analysis utilizes Excel’s built-in features such as pivot tables, pivot charts, and statistical formulas to generate insights and to extract churn patterns against different required criteria.

## Contents
1. [Objective](#objective)
2. [Meta Data](#meta-data)
3. [Methodology](#methodology)
4. [Excel File Overview](#excel-file-overview)
5. [How to Use](#how-to-use)
6. [Results](#results)

## Objective
The goal of this churn analysis is to identify key factors influencing customer churn for sample customer data provided by Databel, to visualize churn patterns, and build insights that can help the telecom company in reducing churn. The historical customer data provided was used to analyze trends and calculate churn rates across different categories like demographics, customer subscribed plans, and service usage.

## Data
The dataset includes various customer attributes that are crucial for identifying churn risk, such as:
- Customer ID
- Age
- Gender
- State
- Extra monthly charges (including data & calling charges)
- Tenure (how long the customer has been with the company)
- Monthly data usage (with specification to whether customer subscriped into Unlimited Plans)
- Customer service interactions
- Churn status (whether the customer has churned or not)
- Churn reasons (further grouped into categories)
- Service & Device protection

The data used for this analysis can be found in the `Customer_Data.xlsx` file included in the repository.

## Methodology
The churn analysis involves the following steps:
1. **Data Cleaning & Exploring**: Transform ranges into tabulated form & removing any duplicate data.
2. **Churn Rate Calculation**: Calculate the churn rate by dividing the number of customers who have churned by the total number of customers.
3. **Segment Analysis**: Group data based on different segments such as customer age, gender, and tenure. This allows for identifying specific patterns or trends that influence churn.
4. **Predictive Insights**: Using pivot tables, we can identify risk factors correlated with higher churn rates by visualizing the results through charts.
5. **Visualization**: Charts and graphs (e.g., column charts, pie charts) are used to show the churn rate by segment.

## Excel File Overview
The project consists of the following tabs in the Excel workbook:

1. **Dashboard**: A high-level dashboard summarizing the churn rate and key insights, including charts showing churn across different customer segments..
2. **Aggregate**: The customer information & data after cleaning, with no duplicated values.
3. **Customer**: The customer usage & subcription information, with no duplicated values.
4. **Customer_Pivots**: Pivot tables, formulas, and visualizations that help identify churn patterns.
5. **Aggregate_Pivots**: Pivot table & charts focusing on demographics & tenure.
6. **Original Data**: Placed in original form as recieved from Databel (under file name 'Customer_Data.xlsx').

## How to Use
1. **Download the Excel File**: You can download the `Customer_Churn_Analysis.xlsx` file from this repository.
2. **Open in Excel**: Open the Excel file using Microsoft Excel or any compatible spreadsheet software.
3. **Data Review**: Review the data and understand the structure of customer attributes.
4. **Analysis**: Use the pivot tables and charts in the "Dashboard" tab to explore churn patterns and trends.

## Results
After performing the churn analysis, some key insights include:
- Churn rates tend to be higher among older customers.
- Customers with no international plans subscriptions tend to have a higher likelihood of churning.
- Shorter tenure periods correlate with a higher likelihood of churn.
  
These insights help to focus retention strategies on high-risk customer segments.

---

For any inquiries please contact me on mohamad.arqam1@gmail.com
