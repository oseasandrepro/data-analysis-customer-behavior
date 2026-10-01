# Retail Customer Behavior Analysis & Interactive Dashboard

Transforming retail transaction and customer data into actionable business insights through exploratory data analysis and interactive visualizations. The dashboard provides an overview of key performance indicators (KPIs), including total customers, average purchase amount, and revenue distribution across age groups, product categories, and gender.

It enables users to explore business questions such as: What proportion of customers are subscribers versus non-subscribers? How does revenue vary across age groups? Which product categories contribute the most to total revenue?

Key technical components: Data exploration and analysis using Python and SQL; Customer segmentation and purchasing behavior analysis; Interactive dashboard development for KPI monitoring and business decision support.

**Insted of Use Power BI I decide to use Superset as business intelligence tool**
Because it is open-source and it can be configured locally with PostgreSQL or other database so this repository cold work as path way for an "stand alone" solution for pratice of: Data exploration and analysis and Interactive dashboard development.

---

"[Apache Superset](https://superset.apache.org/) is an open-source modern data exploration and visualization platform.
Superset is fast, lightweight, intuitive, and loaded with options that make it easy 
for users of all skill sets to explore and visualize their data, from simple line charts
to highly detailed geospatial charts."

**Funtionaly the Superset dashboard is identical to Power BI. Implemented Dashboard:**

<img src="images/v1dashboard_1.png?raw=true" />

## Set up environment

Check how to set up PostgreSQL and Apache Superset [here](./set-up-postgresql-and-superset.md)

Check the Data exploration and analysis using Python and SQL in [this notebook](./customer-shopping-behavior-analysis.ipynb)
This file contains:
 - Data Import
 - Data exploration
 - Data cleaning
 - Connection to SQL Database



[Reference Project](https://github.com/amlanmohanty1/customer-trends-data-analysis-SQL-Python-PowerBI)
