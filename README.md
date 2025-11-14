# customer_behavior_analysis
Business Analytics project showcasing customer behavior analysis using Python, SQL and PowerBI

Customer Shopping Behavior Analysis — Complete Business Analytics Project
📌 Overview

This project presents a full end-to-end business analytics workflow, starting from raw data ingestion in Python to generating business-ready insights through SQL analysis, interactive Power BI dashboards, and a final presentation built using Gamma.
The objective is to decode customer shopping patterns and translate them into actionable business intelligence that supports strategic decision-making.

📂 Dataset

Name: Customer Shopping Behavior

Format: CSV

Records: ~3,900+ rows (cleaned and validated)

Features Include:

Customer demographics

Purchase behavior

Payment preference

Shopping frequency

Location insights

Product category patterns

This dataset is attached and also utilized directly in the Jupyter Notebook.

🛠 Tools & Technologies
Category	Tools
Programming	Python (Jupyter Notebook)
Libraries Used	Pandas, NumPy, Matplotlib, Seaborn, SQLAlchemy
Database	PostgreSQL + pgAdmin 4
SQL	DDL, DML, Aggregations, Joins, Window Functions
Visualization	Power BI
Presentation	Gamma
Reporting	Power BI Report + Executive Summary
🔍 Project Workflow (Step-by-Step)
1. Data Loading (Python)

Loaded the dataset using Pandas

Performed initial structural checks (info(), head(), schema validation)

2. Exploratory Data Analysis (EDA)

Summary statistics, missing value treatment, outlier profiling

Customer segmentation visuals

Category-wise purchase trends

Seasonal and payment behavior decomposition

3. Data Cleaning

Removed duplicates

Standardized column formats

Imputed missing values (mean/median/mode depending on variable type)

Encoded categorical variables where needed

4. Database Integration (PostgreSQL)

Created a PostgreSQL database

Loaded the cleaned dataset using SQLAlchemy

Executed custom SQL queries to uncover:

Spending patterns

High-value customer segments

Most profitable categories

Payment mode distribution

Location-wise demand insights

5. Power BI Dashboard

Designed a multi-page, interactive dashboard showcasing:

Sales Overview

Demographics Breakdown

Category & Product Insights

Customer Behavior Analysis

Payment Behavior Heatmaps

Forecasting & Trend Lines

6. Report & Presentation

Built a structured, insights-driven Power BI Report

Prepared a forward-looking Gamma Presentation summarizing:

Executive insights

Key KPIs

Actionable recommendations

Visual storytelling for stakeholders

📊 Key Insights (Business Results)

Identified core customer segments contributing to majority revenue

Uncovered high-conversion product categories

Analyzed customer repeat behavior & loyalty patterns

Mapped geographically strong & weak performing regions

Revealed opportunities to optimize marketing, pricing, and inventory planning

▶️ How to Run the Project
1. Clone the Repository
git clone <your-repository-link>
cd customer-shopping-behavior-analysis

2. Run Jupyter Notebook
jupyter notebook Customer_Shopping_Behavior_Analysis.ipynb

3. Set Up PostgreSQL

Import the SQL file: customer_behavior_postgres.sql

Run all queries to reproduce analytical results

4. View Dashboard (Power BI Desktop)

Open the .pbix file

Refresh data source connection if required

5. Presentation

Open the Gamma link or use the exported PDF/PPT version

📁 Repository Structure
├── data/
│   └── customer_shopping_behavior.csv
├── notebooks/
│   └── Customer_Shopping_Behavior_Analysis.ipynb
├── sql/
│   └── customer_behavior_postgres.sql
├── dashboard/
│   └── PowerBI_Customer_Behavior.pbix
├── presentation/
│   └── Gamma_Presentation.pdf (or link)
└── README.md

📞 Contact

For collaboration or opportunities, feel free to reach out.
