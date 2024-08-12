# churned-customers-dashboard
![Dashboard  Overview](https://github.com/waleed-analyst/churned-customers-dashboard/blob/main/dashboard%20overview.png)



# Telecom Customer Churn Analysis Dashboard

This repository contains the Power BI dashboard created for a telecom company. The dashboard provides comprehensive insights into customer churn, identifying at-risk customers, reasons for churn, and strategies to decrease churn rates. The visualizations help stakeholders make informed decisions to improve customer retention.

## Table of Contents

- [Dataset](#dataset)
- [Data Model](#data-model)
- [Project Overview](#project-overview)
- [Creation Process](#creation-process)
- [Questions Addressed](#questions-addressed)
- [Conclusion](#conclusion)

## Dataset

The dataset includes various customer and service details:
- **CustomerID**
- **Gender**
- **Age**
- **Marital Status**
- **Number of Dependents**
- **City**
- **Zip Code**
- **Latitude**
- **Longitude**
- **Number of Referrals**
- **Tenure in Months**
- **Offer**
- **Phone Service**
- **Avg Monthly Long Distance Charges**
- **Multiple Lines**
- **Internet Service**
- **Internet Type**
- **Avg Monthly GB Download**
- **Online Security**
- **Online Backup**
- **Device Protection Plan**
- **Premium Tech Support**
- **Streaming TV**
- **Streaming Movies**
- **Streaming Music**
- **Unlimited Data**
- **Contract**
- **Paperless Billing**
- **Payment Method**
- **Monthly Charge**
- **Total Charges**
- **Total Refunds**
- **Total Extra Data Charges**
- **Total Long Distance Charges**
- **Total Revenue**
- **Customer Status**
- **Churn Category**
- **Churn Reason**
- **Population**

## Data Model

The data model follows a star schema, optimized for analytical queries:

- **Fact Table**: Customer Details
- **Dimension Tables**: peyment_method, churned_cat, internet_type, city

## Project Overview

This project focuses on analyzing customer churn for a telecom company using a comprehensive dataset. The dashboard provides insights into customer demographics, service usage, and billing information, identifying key factors contributing to churn. By visualizing churn patterns and highlighting at-risk customers, the dashboard aids in developing strategies to enhance customer retention and reduce churn rates.

### Dataset Description

The dataset provided includes detailed information about telecom customers, their service usage, and billing details. The goal is to analyze customer churn and understand factors influencing customer retention.

### Users of the Dashboard

The primary users of this dashboard are stakeholders and decision-makers at the telecom company, including:

- **Executives**: Interested in overall churn rates and financial impacts.
- **Customer Service Managers**: Focused on identifying at-risk customers and reasons for churn.
- **Operations Managers**: Monitoring service usage and customer satisfaction.

## Creation Process

### Data Import and Preparation
Imported and cleaned the raw dataset using Power Query in Power BI. This involved data cleansing, transformation, and shaping to fit the analytical model.

### Data Modeling
Constructed a star schema to optimize data relationships and facilitate efficient analytical queries. Defined calculated columns and measures to enrich the dataset.

### Analysis with DAX
Utilized Data Analysis Expressions (DAX) to calculate key performance indicators (KPIs), aggregated metrics, and perform advanced calculations supporting decision-making.

### Data Visualization
Crafted compelling and intuitive visualizations using Power BI’s robust tools. Designed visually appealing representations of the data, making it easy for stakeholders to interpret and derive actionable insights.

## Questions Addressed

- **What is the total number of customers?**
  - Solution: KPI card showing total customer count.
- **What is the average monthly charge for all customers?**
  - Solution: KPI card showing average monthly charge.
- **How many customers use phone or internet services?**
  - Solution: Pie chart showing the distribution of users by service type.
- **What are the reasons for customer churn?**
  - Solution: Bar chart showing the distribution of churn reasons.
- **Who are the at-risk customers?**
  - Solution: Table highlighting customers with high churn risk based on defined conditions.

## Conclusion

This dashboard provides a detailed analysis of customer churn, enabling stakeholders to identify at-risk customers, understand churn reasons, and develop strategies to improve customer retention. The use of various Power BI features, including DAX measures and interactive visualizations, ensures a comprehensive understanding of the factors influencing customer churn.
