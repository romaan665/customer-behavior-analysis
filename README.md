# customer-behavior-analysis
Data Analytics Project

Overview
This project demonstrates an end-to-end data analytics workflow, starting from data loading and preprocessing in Python to data visualization in Power BI. The project focuses on cleaning, analyzing, and transforming raw data into meaningful business insights using Python, PostgreSQL, SQL, and Power BI.

Dataset
The dataset contains customer-related information used for exploratory data analysis, data cleaning, SQL querying, and dashboard creation.

Data includes:
Customer demographics
Purchase behavior
Transaction details
Other business-related attributes

Tools & Technologies:
Python
Pandas
NumPy
Matplotlib
PostgreSQL
SQL
SQLAlchemy
Power BI

Project Workflow
1. Data Loading
Imported the dataset into Python using Pandas.
Loaded the cleaned dataset into a PostgreSQL database using SQLAlchemy.

3. Exploratory Data Analysis (EDA)
Performed initial analysis to understand the dataset by:
Checking data types
Identifying missing values
Finding duplicate records
Reviewing summary statistics
Exploring data distributions

3. Data Cleaning
Prepared the dataset by:
Handling missing values
Removing duplicate records
Correcting inconsistent data
Converting data types where necessary
Preparing the data for analysis

4. SQL Analysis
Executed SQL queries in PostgreSQL to analyze the dataset, including:
Filtering records
Sorting data
Aggregate functions
GROUP BY and HAVING
JOIN operations
Business insight queries

5. Dashboard Development
Built an interactive Power BI dashboard to visualize key insights using:
Cards
Bar Charts
Line Charts
Pie Charts
Slicers and Filters

The dashboard provides insights into:
Customer distribution
Sales and revenue trends
Customer purchasing behavior
Category-wise performance
Key business KPIs
Interactive filtering for better analysis

Results
This project demonstrates how raw data can be transformed into meaningful business insights through:
Data cleaning and preprocessing
SQL-based data analysis
Interactive Power BI visualizations
Data-driven decision making

Project Structure
Data-Analytics-Project/
│
├── dataset/
│   └── customer_data.csv
│
├── notebooks/
│   └── Data_Analysis.ipynb
│
├── sql/
│   └── analysis_queries.sql
│
├── powerbi/
│   └── Dashboard.pbix
│
├── images/
│   └── dashboard.png
│
├── README.md

How to Run
1. Clone the repository
git clone <repository-url>
2. Install dependencies
pip install -r requirements.txt
3. Configure PostgreSQL
Install PostgreSQL.
Create a new database.
Update the database credentials in the Python script.
4. Load the dataset
Run the Python script or Jupyter Notebook to:
Load the dataset
Perform data cleaning
Import the processed data into PostgreSQL
5. Execute SQL Queries
Run the SQL scripts in PostgreSQL to perform analysis and generate insights.
6. Open Power BI Dashboard
Open the .pbix file in Power BI Desktop and refresh the data connection if needed.

Skills Demonstrated
Data Cleaning
Exploratory Data Analysis (EDA)
SQL Querying
PostgreSQL Database Management
Data Visualization
Dashboard Development
Python Programming
Business Intelligence
Data Analytics Workflow
Future Enhancements
Automate the ETL process
Add advanced SQL queries using window functions
Integrate predictive analytics using machine learning


Author
Umm E Romaan Shaikh
Technologies: Python • PostgreSQL • SQL • Power BI • Pandas • NumPy • SQLAlchemy
