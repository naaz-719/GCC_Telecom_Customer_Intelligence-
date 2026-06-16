![background](screenshots/bg.png)

# GCC Telecom Customer Intelligence & Revenue Protection Platform
## Project Overview
An end-to-end Telecom Customer Intelligence Platform built using Databricks, Lakeflow Designer, Machine Learning, Streamlit, and Generative AI.
The platform helps telecom operators identify high-risk customers, protect revenue, improve retention strategies, and provide executive-level business intelligence through interactive dashboards and AI-powered recommendations.
________________________________________

## Live Demo

- 🌐 Live Application: [App](https://telecomgccgit-2cymk4ufe8uu8z5wo2indk.streamlit.app/)
- 📊 Power BI Dashboard: [Dashboard Link](https://app.fabric.microsoft.com/links/41Qp938tCH?ctid=880db91c-d2b8-4752-96bb-ec6f76398bf3&pbi_source=linkShare)
- 💻 GitHub Repository: [Project Repository](https://github.com/naaz-719/GCC_Telecom_Customer_Intelligence-)


________________________________________
## Business Problem

- Telecom operators face significant challenges in:
   * Customer churn
   * Revenue leakage
   * Declining customer engagement
   * Delayed retention actions
   * Lack of executive visibility
- This project provides a unified analytics platform to:
   * Predict customer churn risk
   * Identify revenue at risk
   * Monitor customer health
   * Enable proactive retention strategies
   * Deliver executive decision support through AI-generated insights
________________________________________
## Solution Architecture

Raw Telecom Dataset 
      ↓ 
Databricks Lakehouse

Bronze Layer (telecom_data_raw)
      ↓
Silver Layer (silver_gcc_data)
      ↓
Feature Engineering
  * Customer Health Score
  * Revenue At Risk
  * Revenue Segment
  * Tenure Segment
  * Risk Classification
      ↓
Gold Layer
  * gold_customer_master
  * gold_customer_churn
  * gold_customer_360
  * gold_retention
  * gold_revenue_summary
      ↓
Streamlit Analytics Platform
      ↓
AI Copilot & Executive Intelligence
________________________________________
## Technology Stack

#### Data Engineering
  * Databricks Lakehouse
  * Databricks Lakeflow Designer
  * Delta Tables
  * PySpark
  * Pandas
#### Machine Learning
  * Scikit-Learn
  * Logistic Regression
  * Churn Risk Scoring
#### Dashboarding
  * Streamlit
  * Plotly
  * Python
#### AI
  * Groq API
  * Llama 3.3 70B
  * Executive AI Advisor
  * Revenue Protection AI Copilot
  * Customer Retention AI Assistant
________________________________________
## Dataset Information

#### Customer-level telecom dataset containing:
  * Customer Demographics
  * Service Information
  * Contract Details
  * Billing Information
  * Churn Information
  * Customer Lifetime Value
  * Complaint History
  * Payment Delays
  * Network Quality Metrics
  * App Engagement Metrics
  * Roaming Usage
#### Dataset Size:
  * 7,043 Customers
  * Multi-country GCC telecom portfolio
#### Countries Included:
  * Saudi Arabia
  * UAE
  * Oman
  * Bahrain
  * Kuwait
  * Qatar
________________________________________
## Medallion Architecture

Bronze Layer
Table:
telecom_data_raw
Purpose:
  * Raw ingestion layer
  * Original source data
  * No transformations
________________________________________
## Silver Layer
Table:
silver_gcc_data
Transformations:
•	Data quality checks
•	Missing value handling
•	Standardization
•	Data cleansing
•	Feature preparation
________________________________________
## Gold Layer
*gold_customer_master*
Master customer profile table.
Contains:
  * Customer demographics
  * Contract information
  * Customer segmentation
________________________________________
*gold_customer_churn*
Churn-focused customer table.
Contains:
  * Churn indicators
  * Churn reasons
  * Risk classifications
________________________________________
*gold_customer_360*
Executive customer intelligence table.
Contains:
  * Customer profile
  * CLTV
  * Health score
  * Revenue risk
  * Risk segment
________________________________________
*gold_retention*
Retention-focused customer table.
Contains:
  * Engagement metrics
  * Complaints
  * Payment behavior
  * Retention indicators

![Lakeflow Pipeline](screenshots/pipeline.png)
________________________________________
*gold_revenue_summary*
Aggregated executive revenue table.
Contains:
  * Revenue by country
  * Revenue by customer type
  * Revenue exposure
  * Customer distribution
________________________________________
## Feature Engineering
Customer Health Score
Custom metric developed to evaluate overall customer health.
Factors considered:
  * Complaints
  * Payment delays
  * Network quality
  * App engagement
  * Usage behavior
Purpose:
  * Early risk detection
  * Customer prioritization
________________________________________
## Risk Segmentation
Customers classified into:
High Risk
Immediate retention intervention required.
Medium Risk
Monitor and engage.
Low Risk
Healthy customer base.
________________________________________
## Revenue At Risk
Business metric estimating potential revenue loss from customer churn.
Used to:
•	Prioritize retention budgets
•	Quantify financial exposure
•	Support executive decision making
________________________________________
## Streamlit Analytics Platform
The solution includes a fully interactive Streamlit application.
Modules:
Home Dashboard
Executive KPI overview.
Metrics:
  * Total Customers
  * Average CLTV
  * Customer Health Score
  * High Risk Customers
  * Revenue At Risk
  * Potential Revenue Recovery
________________________________________
## Executive Analytics Dashboard
Executive-level business intelligence.
Features:
  * Portfolio risk analysis
  * Revenue exposure analysis
  * Country-level risk monitoring
  * Customer-type risk assessment
  * AI Executive Advisor
________________________________________
## Customer Insights
360-degree customer intelligence.
Features:
  * Customer profile
  * Customer health score
  * Churn risk analysis
  * Customer segmentation
  * AI Customer Copilot
________________________________________
## Revenue Protection Dashboard
Revenue-risk management module.
Features:
  * Revenue exposure tracking
  * High-value customer monitoring
  * Revenue protection opportunities
  * AI Revenue Advisor
________________________________________
## AI Recommendations
Generative AI-powered telecom consultant.
Capabilities:
  * Customer churn analysis
  * Retention strategy generation
  * Revenue protection recommendations
  * Next-best-action suggestions
  * Executive summaries
Powered by:
  * Groq API
  * Llama 3.3 70B
________________________________________
## Key Business Insights Generated
The platform enables identification of:
  * High-risk customer segments
  * Revenue leakage opportunities
  * Customer engagement issues
  * Retention priorities
  * Country-level churn exposure
  * Customer-type performance
________________________________________
## Business Impact
Potential outcomes include:
  * Reduced customer churn
  * Improved retention campaigns
  * Better revenue protection
  * Increased customer lifetime value
  * Faster executive decision making
  * Enhanced customer experience
________________________________________
## Project Highlights
  ✔ End-to-End Telecom Analytics Solution
  ✔ Databricks Lakehouse Architecture
  ✔ Lakeflow Designer Pipeline
  ✔ Medallion Data Architecture
  ✔ Customer 360 Intelligence
  ✔ Revenue Protection Analytics
  ✔ AI-Powered Executive Advisor
  ✔ Interactive Streamlit Dashboards
  ✔ Business-Oriented KPI Framework
  ✔ Recruiter-Friendly Portfolio Project
________________________________________
# Future Enhancements
  *	Real-time streaming ingestion
  *	MLflow model deployment
  *	Automated model retraining
  *	Customer propensity modeling
  *	GenAI chatbot integration
  *	Databricks Model Serving
  *	Real-time churn monitoring
________________________________________
Author
Naaz
Computer Science (AI & ML) Graduate
Specialization: Data Analytics, Machine Learning, Business Intelligence, Databricks, Power BI, Python


