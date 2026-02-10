# Data-Analyst-Internship-Task-14

# Task 14 – ETL Mini Pipeline (Python)

## About this task

In this task, I created a small ETL pipeline using Python and pandas.

ETL means:
Extract → Transform → Load

The main goal is to take raw data, clean it, and store it in a structured format so that it can be used for analysis.

---

## What I did step by step

### Step 1 – Extract
First, I loaded the retail sales dataset (CSV file) into Python using pandas.

---

### Step 2 – Transform
Then I cleaned the data by:
- Removing duplicate rows
- Filling missing values
- Standardizing column names
- Converting numeric columns to correct datatypes
- Creating new columns like:
  - total_sales
  - profit
  - segment (High/Low sales)

  ---

### Step 3 – Load
After cleaning:
- Saved the processed dataset into a new CSV file
- Split the data into separate tables (customers, products, orders)
- Stored all tables inside an SQLite database

---

## Tools used
- Python
- pandas
- SQLite
- Google Colab / Jupyter Notebook

---

## Files in this project

- task14_etl.ipynb → ETL code
- retail_sales_dataset.csv → raw dataset
- processed_data.csv → cleaned dataset
- customers.csv → customer details
- products.csv → product details
- orders.csv → order data
- database.sqlite → database with all tables
- README.md → project explanation

---

## Final result

Finally, I successfully built an end-to-end ETL pipeline.

Now the raw data is:
  cleaned  
  organized  
  stored in tables  
  ready for analysis  

This task helped me understand how ETL works in real-world data analytics projects.
