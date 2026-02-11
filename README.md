# Automated-Business-Intelligence-KPI-Reporting-Pipeline
Ovrerview
This project is an automated Business Intelligence (BI) pipeline built using n8n to process, clean, and analyze lead data from Google Sheets. 
The workflow performs data transformation, KPI calculation, and daily snapshot storage to enable automated business performance tracking.

Problem Statement
Manual KPI tracking in spreadsheets is time-consuming and error-prone.
This project automates:
* Data cleaning
* KPI computation
* Snapshot generation
* Dashboard-ready reporting
  
Workflow Architecture:
Google Sheets (Lead Data)
        ↓
n8n Automation
        ↓
Data Cleaning & Standardization
        ↓
KPI Computation (JavaScript)
        ↓
Daily Snapshot Storage
        ↓
Dashboard-ready Metrics Sheet

Key Features
Automated data ingestion from Google Sheets
Text standardization (region, sales stage, lead source)
KPI calculations:
* Total Leads
* Total Pipeline Value
* Average Deal Value
* Conversion Rate
Daily snapshot logic for historical tracking
Data quality checks for anomaly detection

Tech Stack:
*n8n (workflow automation)
*JavaScript (KPI logic)
*Google Sheets (data source & reporting)
*Data Cleaning & Transformation
*Business Intelligence concepts

KPIs Calculated:
*Total Leads – Count of records
*Total Pipeline Value – Sum of estimated deal values
*Average Deal Value – Mean pipeline size
*Conversion Rate (%) – Converted leads / Total leads

What I Learned:
*Building automated data pipelines
*Data normalization and cleaning logic
*KPI modeling and metric computation
*Snapshot-based performance tracking
*Designing dashboard-ready datasets

Files Included:
workflow.json – Exported n8n automation workflow

Future Improvements:
*Integration with a live database (PostgreSQL)
*Automated BI dashboard publishing
*Advanced anomaly detection alerts
*Cloud deployment for continuous execution

How to Run:
*Install n8n
*Import workflow.json
*Connect Google Sheets credentials
*Execute workflow

Contact
Feel free to connect for collaboration or discussion on automation & BI systems.
