# GCC Telecom Customer Churn Intelligence & Revenue Protection Platform

## Project Overview

An end-to-end Telecom Customer Churn Prediction, Risk Segmentation, Revenue Protection, and AI-Powered Decision Intelligence Platform built using Data Engineering, Machine Learning, Generative AI, Databricks, Microsoft Fabric, and Streamlit.

The platform enables telecom executives, customer retention teams, and revenue managers to identify customers at risk of churn, estimate revenue exposure, prioritize retention actions, and generate AI-powered business recommendations.

---

# Business Problem

Telecom companies lose significant revenue due to customer churn.

Traditional reporting provides historical insights but does not proactively identify:

* Which customers are likely to churn
* How much revenue is at risk
* Which customer segments require intervention
* What actions should be taken to reduce churn

This project addresses those challenges through predictive analytics, customer intelligence, revenue protection, and AI-powered recommendations.

---

# Project Objectives

* Predict customer churn probability
* Identify high-risk customers
* Calculate customer health scores
* Estimate revenue at risk
* Segment customers by business risk
* Generate executive-level business insights
* Provide AI-powered recommendations for retention and revenue protection

---

# Technology Stack

## Data Engineering

* Microsoft Fabric
* Databricks
* Lakehouse Architecture
* Databricks Lakeflow Designer
* Delta Tables

## Data Analysis

* Python
* Pandas
* NumPy

## Data Visualization

* Plotly
* Streamlit

## Machine Learning

* Scikit-Learn
* Logistic Regression

## Generative AI

* Groq API
* Llama 3.3 70B Versatile
* AI Executive Advisor
* AI Customer Copilot
* AI Revenue Protection Advisor

---

# Dataset Overview

Telecom customer dataset containing:

* Customer Demographics
* Customer Contracts
* Service Usage
* Billing Information
* Churn Information
* Revenue Information
* Customer Engagement Metrics
* Network Quality Metrics

### Original Features

* customer_id
* country
* city
* gender
* senior_citizen
* partner
* dependents
* tenure_months
* phone_service
* multiple_lines
* internet_service
* online_security
* online_backup
* device_protection
* tech_support
* streaming_tv
* streaming_movies
* contract
* paperless_billing
* payment_method
* monthly_charge
* total_charges
* churn_label
* churn_value
* churn_score
* cltv
* churn_reason
* customer_type
* complaint_count
* payment_delay_days
* roaming_usage
* app_logins
* network_quality_score
* avg_monthly_data_usage_gb
* arpu

---

# Feature Engineering

The following business features were created:

## Revenue Segment

Customers categorized into:

* Low Revenue
* Medium Revenue
* High Revenue

Based on CLTV values.

---

## Tenure Segment

Customers categorized into:

* New Customer
* Growing Customer
* Loyal Customer

Based on tenure months.

---

## Customer Health Score

Custom business metric created using:

* Complaints
* Payment Delays
* App Engagement
* Network Quality

Used to measure overall customer health.

---

## Risk Segment

Customers categorized as:

* High Risk
* Medium Risk
* Low Risk

Based on churn probability and customer behavior.

---

## Revenue At Risk

Estimated using:

Revenue At Risk = CLTV × Risk Weight

Risk Weights:

* High Risk = 60%
* Medium Risk = 30%
* Low Risk = 10%

---

# Machine Learning Pipeline

## Model Used

Logistic Regression

### Why Logistic Regression?

* Highly interpretable
* Fast training
* Strong baseline model
* Suitable for churn prediction

---

## Model Output

The model predicts:

* Churn Probability
* Churn Risk Classification

for every customer.

---

# Databricks Lakehouse Architecture

Implemented using Medallion Architecture.

## Bronze Layer

Raw telecom customer data.

Table:

telecom_data_raw

Purpose:

* Raw data ingestion
* Source of truth

---

## Silver Layer

Cleaned and transformed data.

Table:

silver_gcc_data

Transformations:

* Null handling
* Duplicate removal
* Feature engineering
* Data quality improvements

---

## Gold Layer

Business-ready analytics layer.

Table:

gold_gcc_data

Contains:

* Churn Intelligence
* Revenue Analytics
* Customer Intelligence
* Executive KPIs

---

# Databricks Lakeflow Designer

Visual data pipeline created using:

Bronze Layer
↓
Silver Layer
↓
Gold Layer

Pipeline automates data transformation across the Medallion Architecture.

---

# Streamlit Application

Interactive telecom analytics platform.

---

## Home Page

Portfolio overview including:

* Total Customers
* High Risk %
* Revenue At Risk
* Average CLTV
* Customer Health Score

---

## Customer Insights

360-degree customer intelligence view.

Includes:

* Customer Profile
* Churn Prediction
* Risk Drivers
* Revenue Exposure
* Customer Health Score
* AI Customer Copilot

---

## Executive Analytics Dashboard

Enterprise-level dashboard containing:

### Risk Analytics

* Risk Distribution
* Risk Rate by Country
* Risk Rate by Customer Type

### Customer Analytics

* Customer Concentration Analysis
* Customer Segment Analysis
* Health Score Analysis

### Revenue Analytics

* Revenue Exposure
* Revenue by Country
* Revenue at Risk

### AI Executive Advisor

Generative AI powered portfolio intelligence including:

* Executive Summary
* Risk Intelligence
* Customer Intelligence
* Revenue Intelligence
* Strategic Recommendations

---

## Risk Segmentation

Portfolio-wide risk analysis.

Includes:

* High Risk Customers
* Medium Risk Customers
* Low Risk Customers
* Risk Trends
* Risk Distribution

---

## Revenue Protection

Revenue-focused business intelligence.

Includes:

* Revenue Exposure Analysis
* High Value Customers at Risk
* Revenue Concentration Analysis
* Revenue Recovery Opportunities

### AI Revenue Protection Advisor

Provides:

* Revenue Risk Assessment
* Revenue Recovery Strategies
* Retention Prioritization
* Business Recommendations

---

## Model Performance

Machine Learning model evaluation.

Metrics include:

* Accuracy
* Precision
* Recall
* F1 Score

Visualization includes:

* Confusion Matrix
* Model Performance Dashboard

---

# AI Capabilities

## AI Customer Copilot

Analyzes individual customers and provides:

* Risk Analysis
* Retention Strategy
* Revenue Protection Actions
* Next Best Actions

---

## AI Executive Advisor

Analyzes entire telecom portfolio and generates:

* Executive Summary
* Portfolio Risk Assessment
* Revenue Intelligence
* Strategic Recommendations

---

## AI Revenue Advisor

Provides:

* Revenue Protection Strategy
* Revenue Recovery Opportunities
* Immediate Revenue Actions

---

# Business Value

The platform enables organizations to:

* Reduce customer churn
* Protect recurring revenue
* Improve customer retention
* Prioritize retention campaigns
* Optimize customer engagement
* Generate executive-level business insights
* Support data-driven decision making

---

# Future Enhancements

* Real-time streaming data
* Automated retraining pipeline
* Customer lifetime value prediction
* Explainable AI (XAI)
* Recommendation Engine
* Customer Next Best Action Model
* Power BI Integration
* Azure Deployment
* Enterprise CI/CD Pipeline

---

# Author

Naaz Hafiz Mulla

Computer Science (AI & ML)
Honors in Data Science

Specialization Areas:

* Data Analytics
* Data Science
* Machine Learning
* Business Intelligence
* Telecom Analytics
* AI-Powered Decision Intelligence
