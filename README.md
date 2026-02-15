# Customer Churn Risk Analysis

## 📊 Overview
This project analyzes customer churn patterns to identify high-risk segments and quantify revenue exposure.
The objective is to design a decision-focused Business Intelligence dashboard that supports retention strategy and risk prioritization.

## 🎯 Business Objective
* Measure overall churn rate and revenue at risk
* Identify the strongest churn drivers
* Segment customers based on behavioral risk indicators

## 🔎 Key Insights
* Churn risk is significantly higher among **inactive customers**.
* Customers with a **single product** show elevated churn probability.
* **High-value customers** represent substantial financial exposure when churn occurs.
* Revenue at risk is most concentrated in **Germany**.
* Risk segments combining behavioral indicators provide stronger prioritization than standalone demographics.

## 🧠 Analytical Approach
#### 1️⃣ Exploratory Analysis
#### 2️⃣ Feature Engineering
Created behavioral flags:
* `single_product_flag`
* `low_engagement_risk_flag`
* `high_value_risk_flag`
These composite indicators strengthened churn signal detection compared to raw attributes alone.
#### 3️⃣ Risk Segmentation
