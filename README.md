# Consumer Behavior Data Analysis

A data-driven portfolio project that explores customer shopping behavior using Python, SQL, and business analytics techniques. The objective is to transform raw retail data into meaningful insights related to purchasing patterns, customer segmentation, revenue generation, and promotional effectiveness.

## Project Summary

This project demonstrates an end-to-end analytics workflow, from data preparation and feature engineering to SQL-based analysis and business reporting. It highlights how structured customer data can be used to answer practical questions such as:

- Which customer segments contribute the most revenue?
- How do discounts and subscriptions influence spending behavior?
- Which products and categories are most frequently purchased?
- How do shipping methods and product preferences vary across customer groups?

## What I Built

- Cleaned and prepared a retail customer dataset for analysis
- Performed exploratory data analysis in Python using Pandas
- Engineered new features such as age groups and purchase frequency categories
- Loaded the transformed dataset into PostgreSQL
- Wrote SQL queries to answer business-focused analytics questions

## Dataset

The project uses the customer shopping behavior dataset located at [dataset/customer_shopping_behavior.csv](dataset/customer_shopping_behavior.csv). The data includes customer demographics, purchase details, product categories, review ratings, subscription status, shipping preferences, and discount usage.

## Tools and Technologies

- Python
- Jupyter Notebook
- Pandas
- SQL
- PostgreSQL
- SQLAlchemy
- psycopg2
- Python-dotenv

## Repository Structure

- [customer-behavior-analysis.ipynb](customer-behavior-analysis.ipynb) – Main notebook for data cleaning, transformation, and database loading
- [analysis/customer_behavior_sql_queries.sql](analysis/customer_behavior_sql_queries.sql) – SQL queries for business analysis and reporting
- [dataset/customer_shopping_behavior.csv](dataset/customer_shopping_behavior.csv) – Source dataset
- [documentation](documentation) – Project documentation and supporting materials
- [PBIX](PBIX) – Power BI assets related to the analysis

## Analytics Workflow

1. Load the dataset into a Python environment.
2. Perform data cleaning and validation.
3. Create derived features for deeper analysis.
4. Store the prepared data in PostgreSQL.
5. Use SQL to explore customer behavior and business performance.

## Getting Started

### Prerequisites
- Python 3.x
- Jupyter Notebook
- PostgreSQL

## 🛠️ How to Use This Project

1. **Clone the repository**
   ```bash
   git clone https://github.com/SimbaMunatsi/consumer-behavior-data-analysis.git
   cd consumer-behavior-data-analysis
   python3 -m venv venv
   source venv/bin/activate
   pip install -r requirements.txt
   ```
2. **Open customer-behavior-analysis.ipynb notebook**

    This file contains:

      - Data Import

      - Data exploration

      - Data cleaning

      - Connection to SQL Database
  
3. **Load the data from Python notebook into MySQL/PostgreSQL/MS SQL Server**

      - Create a database in SQL

      - Run Python code to load data into SQL database
  
      - Open **customer_behavior_sql_queries.sql**
  
      - Answer Business Questions using SQL Queries 
      
4. **Connect the SQL Database to Power BI**

      - Open **customer_behavior_dashboard.pbix**
   
      - Create interactive dashboard in Power BI
  
6. **Create Project Report and Presentation**

      - Create project report
   
      - Build presentation deck using Gamma AI


## Why This Project Matters

This repository reflects strong data analytics and business intelligence skills by combining data wrangling, SQL querying, and storytelling with data. It is well suited for showcasing analytical thinking in a professional portfolio.

## Author
Simbarashe Munatsi , Data Scientist | ML Engineer | AI Engineer

## Contacts
Email : vsmunatsi@gmail.com LinkedIn : https://www.linkedin.com/in/victor-simbarashe-munatsi/

## License
This project is licensed under the MIT License. See the LICENSE file for details.