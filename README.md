# Power-BI-Projects
# 📊 Power BI Project Management Dashboard

##  Project Overview
This Power BI dashboard provides operational and performance insights for project and ticket management. It enables team managers to monitor ticket resolution trends, overdue work, workflow throughput, and short-term delivery performance.

The solution was built using automated REST API extraction from a SharePoint-based ticket system and supports daily refresh in Power BI Service.


## ETL & Data Pipeline
- Data source: SharePoint List via REST API
- Extraction: API endpoint connected directly to Power BI
- Refresh: Scheduled daily refresh in Power BI Service
- Transformation:
  - Cleaned ticket status fields
  - Normalized workflow stages
  - Converted date fields for time intelligence analysis
  - Created calculated columns for SLA, overdue flags, and cycle time
- Modeling: Star schema with Date dimension and ticket fact table


## Business Questions Answered
- How many tickets were solved in the past 7 days?
- How many projects or tickets are currently overdue?
- What is the weekly workflow throughput rate?
- Are resolution times improving or slowing down?
- Which teams or categories generate the highest ticket volume?
- What is the trend of open vs closed tickets over time?


## Key KPIs
- Tickets resolved (last 7 days)
- Overdue tickets count
- Average resolution time
- Workflow throughput per week
- Open vs closed ratio
- Tickets by status and priority


## Tools & Techniques
- Power BI Desktop & Service
- REST API ingestion
- Power Query (M) transformations
- DAX time intelligence measures
- Scheduled refresh configuration
- KPI and SLA modeling


## Dashboard Preview
(Add screenshots in /screenshots and link here)


## Skills Demonstrated
- API-based data ingestion
- Automated refresh pipelines
- Operational KPI design
- Time-based performance analytics
- Management-focused dashboard design

# Power BI Coffee Sales Analytics Report

## Project Overview
This Power BI report analyzes transactional coffee shop sales data to identify revenue drivers, product performance, and time-based purchasing behavior. The dashboard supports business decisions in product strategy, staffing, and promotion timing.

The project focuses on structured ETL, clean modeling, and business-question-driven analytics.



## ETL & Data Preparation
- Data source: Raw transactional sales dataset (CSV)
- Cleaning:
  - Removed null and duplicate transactions
  - Standardized product names and categories
  - Corrected date/time formats
- Transformation:
  - Created date and time dimensions
  - Derived hour-of-day and weekday features
  - Calculated revenue and transaction metrics
- Modeling: Fact sales table with Date and Product dimensions



## 🎯 Business Questions Answered
- What are the top 3 products by revenue and volume?
- Which hours of the day generate the most revenue?
- Which days of the week are strongest and weakest?
- What is the average revenue per transaction?
- Which products have high volume but low margin potential?
- How does revenue trend over time?



## Key KPIs
- Total revenue
- Revenue by hour of day
- Top 3 products by revenue
- Transactions per day
- Average order value
- Revenue by weekday



## Tools & Techniques
- Power BI Desktop
- Power Query data cleaning
- DAX measures and ratios
- Time-of-day analytics
- Product performance ranking
- Interactive filtering

---

## Dashboard Preview
(Add screenshots in /screenshots and link here)

---

## Skills Demonstrated
- Transaction data cleaning
- Feature engineering (time bands, weekdays)
- Product performance analytics
- Revenue pattern detection
- Business-driven KPI selection

---
# Power BI AdventureWorks Bike Sales Performance Dashboard

## Project Overview
This Power BI dashboard analyzes the AdventureWorks sales dataset with a focus on bicycle product performance, regional trends, and time-based revenue development. The report demonstrates professional BI modeling, DAX measures, and executive-style KPI reporting.

The goal is to answer core commercial questions a data analyst should address in a sales performance review.

---

## ETL & Data Preparation
- Data source: AdventureWorks sample dataset
- Cleaning:
  - Removed incomplete records
  - Standardized product and territory fields
  - Validated revenue and quantity columns
- Transformation:
  - Built Date dimension table
  - Created product and territory hierarchies
  - Added calculated columns for margins and categories
- Modeling: Star schema with Sales fact and dimension tables

---

## Business Questions Answered
- Which bike categories generate the most revenue?
- Which regions perform best and worst?
- What are the revenue trends by quarter and year?
- What is the revenue growth rate QoQ and YoY?
- Which products drive the highest margins?
- How does average order value change over time?

---

## Key KPIs
- Total bike revenue
- Revenue by region
- Revenue QoQ % and YoY %
- Top products by revenue
- Margin by category
- Average order value

---

## Tools & Techniques
- Power BI Desktop
- Data modeling (star schema)
- DAX time intelligence
- Growth rate calculations
- Ranking and contribution analysis
- Drill-down hierarchies

---

## Dashboard Preview
(Add screenshots in /screenshots and link here)

---

## Skills Demonstrated
- Dimensional data modeling
- Time intelligence DAX
- Sales performance analytics
- Geographic analysis
- Executive KPI reporting



