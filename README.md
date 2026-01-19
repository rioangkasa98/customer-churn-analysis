# 📉 E-Commerce Customer Churn Analysis

## 📌 Project Overview
This project analyzes customer behavior data from an e-commerce platform to understand customer churn patterns and identify opportunities to improve customer retention.
Customer churn can significantly impact revenue, making it important to understand which customer behaviors are linked to higher churn risk.

The analysis focuses on understanding differences between churned and active customers using behavioral, transactional, and engagement data.

## ❓ Business Problem
The business is experiencing customer churn, but the key drivers behind churn are not clearly understood. Without this understanding, it is difficult to design effective retention strategies.

This project aims to answer:
- What patterns differentiate churned customers from active customers?
- Which factors are most strongly associated with churn?
- How can these insights support data-driven retention strategies?

## 🎯 Project Objective
- The objectives of this project are to:
- Analyze customer behavior and engagement patterns
- Identify factors associated with customer churn
- Segment customers based on behavioral characteristics
- Provide data-driven business recommendations

## 📊 Dataset 
The dataset contains customer-level information related to demographics, engagement behavior, and purchase activity.
Data cleaning was performed using Python, and the cleaned dataset is used for all analyses.

## Analysis Summary
The analysis includes:
- Exploratory Data Analysis (EDA)
- Churn distribution analysis
- Feature correlation analysis
- Customer segmentation using K-Means clustering
- Churn rate comparison across customer segments

## Key Insights
- Around 29% of customers have churned, indicating a significant retention challenge
- Customer engagement metrics are strongly related to churn behavior
- Customers with low purchase frequency tend to churn more often
- A high-risk customer segment was identified with a churn rate above 40%
- Highly engaged customers show much lower churn rates
  
<img width="558" height="393" alt="churn_distribution" src="https://github.com/user-attachments/assets/a060321c-39ed-4822-ae14-29bb3fc0c9d0" />

## Business Recommendations
- Focus retention efforts on high-risk customer segments
- Increase engagement for low-activity customers through targeted campaigns
- Encourage repeat purchases with personalized promotions
- Monitor engagement metrics as early indicators of churn

## Customer Segmentation
Customers were segmented using K-Means clustering based on:
- Total purchases
- Average session duration
The segmentation reveals distinct customer groups, ranging from highly engaged and high-value customers to low-engagement customers with minimal activity.

## Customer Segmentation Based on Purchases and Session Duration

<img width="842" height="547" alt="customer_segmentation" src="https://github.com/user-attachments/assets/fbbfd277-f748-4925-a1cd-f080ea3bae16" />

## Churn Rate by Segment

<img width="590" height="390" alt="churn_rate_by_cluster" src="https://github.com/user-attachments/assets/c5ced363-cf5d-4842-983d-55478ff1dce1" />

As shown in the following bar chart, churn rates vary significantly across customer segments. Segment 2, in particular, has a churn rate of approximately 41%, which is the highest among the segments.
