# Customer Churn Analysis Project
comprehensive customer churn analysis project delves into customer behavior through extensive exploratory data analysis (EDA) and machine learning. It identifies key patterns, factors influencing churn, and provides actionable insights for improving customer retention.
The project is enriched with Python Jupyter Notebook and downloadable Power BI and Interactive Tableau dashboard.

## Table of Contents

1. [Introduction](#introduction)
2. [Project Goals](#project-goals)
3. [Data](#data)
   - [Data Sources](#data-sources)
   - [Data Structure](#data-structure)
   - [Data Quality](#data-quality)
4. [Analysis](#analysis)
   - [In-Depth Python Analysis](#in-depth-python-analysis)
   - [Dashboard](#dashboard)
5. [Results](#results)
   - [Exploratory Data Analysis (EDA) Results](#exploratory-data-analysis-eda-results)
   - [Machine Learning Results](#machine-learning-results)
6. [Results and Recommendations](#results-and-recommendations)
   - [Prioritize Tenure](#prioritize-tenure)
   - [Bundle Services](#bundle-services)
   - [Address Online Security Concerns](#address-online-security-concerns)

## Introduction

This repository contains a detailed analysis of customer churn with results and recommendations. The analysis employs both Exploratory Data Analysis (EDA) and Machine Learning (ML) approaches to identify patterns, key factors, and potential strategies to reduce customer churn, including data modeling for visualization.

## Project Goals

1. **EDA Goals:**
   - Explore customer behavior and identify patterns leading to churn.
   - Examine the impact of various services, contract types, and tenure on churn rates.

2. **ML Goals:**
   - Build predictive models to identify factors influencing churn.
   - Predict customers' churn likelihood and identify underlying issues.
   - Provide actionable insights for reducing churn and improving customer retention.

## Data

### Data Sources

The dataset used for this project is sourced from Kaggle, accessible through [this link](https://www.kaggle.com/datasets/blastchar/telco-customer-churn/data). The data is provided under the license, "Data files © Original Authors."

### Data Structure

- Customers who left within the last month (column: Churn)
- Services that each customer has signed up for (e.g., phone, internet, etc.)
- Customer account information (e.g., contract, payment method, monthly charges, total charges)
- Demographic info about customers (e.g., gender, age range, partners, dependents)

### Data Quality

The dataset needs a little cleaning in terms of format; otherwise, the data have good overall quality but are not recent or updated.

## Analysis

### In-Depth Python Analysis
For the detailed analysis, you can access the [Python Jupyter Notebook here](https://github.com/Anas-Adaileh/Customer_Churn_Analytic/blob/main/Customer%20Churn%20Project.ipynb).

### Dashboard
You can download the interactive dashboard for this project using [Power BI Dashboard (Download)](https://drive.google.com/file/d/1nl4MkNzNebye74_InWljeEl-Z-2WYYSa/view?usp=drive_link) or interact with the [Tableau Dashboard Here (Interactive)](https://public.tableau.com/app/profile/anas.adaileh/viz/CustomerChurnDashboard_17023912588670/Dashboard1#2).

## Results

### Exploratory Data Analysis (EDA) Results

1. **Churn Patterns:**
   - Customers with lower tenure and total charges exhibit higher churn rates.
   - Fiber optic service has the highest churn rate, indicating potential issues with quality or pricing.
   - Phone services also show high churn, suggesting a need for tailored packages and competitive pricing.

2. **Critical Churn Services (Pareto Principle):**
   - 80% of customer churn is associated with Phone services, Internet Fiber Optic, Multiple lines, and Streaming services.
   - Recommendations include addressing service quality and exploring more affordable plans.

3. **Contract and Tenure Analysis:**
   - Majority of churn customers opt for month-to-month contracts.
   - Phone services have lower monthly charges but shorter tenure, especially after 20 months.
   - Streaming services contribute to longer tenure, suggesting contract length influences customer retention.

4. **Service Usage and Churn:**
   - Customers with 3 to 6 services, especially those with 3 services, have a higher tendency to churn.

### Machine Learning Results

1. **Clustered Segments for Tailored Services:**
      - *Insight:* Four customer segments have been identified for personalized services.
      - *Recommendation:* Tailor services based on the characteristics of each identified cluster, enhancing customer satisfaction and loyalty.

2. **Top 5 Factors Impacting Churn:**
   - Tenure, Online Security without Internet Service, Number of Services, Paperless Billing, and Payment Method influence customer churn.

3. **Insights and Recommendations:**
   - **Tenure Impact on Churn:**
      - *Insight:* Longer tenure correlates with decreased churn likelihood.
      - *Recommendation:* Implement strategies to reward and encourage customer loyalty.

   - **Online Security Without Internet Service:**
      - *Insight:* Positive coefficient (0.83) indicates higher churn.
      - *Recommendation:* Encourage additional service sign-ups to enhance engagement and retention.

   - **Number of Services and Churn:**
      - *Insight:* Multiple services decrease churn likelihood.
      - *Recommendation:* Promote bundled service packages for added value.

## Results and Recommendations

The combined insights from EDA and ML provide a comprehensive understanding of customer churn. Based on these findings, the following recommendations are derived:

### Prioritize Tenure
Implement loyalty programs and incentives to reward and extend customer tenure.

### Bundle Services
Encourage customers to sign up for additional services, offering bundled packages for enhanced value.

### Address Online Security Concerns
Investigate and address reasons behind increased churn for customers with online security but no internet service.

These recommendations aim to holistically address identified factors influencing churn, providing a strategic approach to improve customer retention. For a more detailed breakdown, refer to the corresponding sections on EDA and ML results, including insights from clustered segments for tailored services.
