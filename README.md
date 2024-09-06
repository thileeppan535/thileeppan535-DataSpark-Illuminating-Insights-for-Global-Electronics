### Project Overview

This project entails a thorough process of cleaning, merging, and analyzing customer, sales, exchange rate, and store data. The workflow is outlined in the following steps:

**Step 0: File Collection**  
All CSV files are collected and stored in a single folder where the Python script will also reside.

**Step 1: Data Cleaning**  
- **Data Reading**: Used Python and Pandas to load the CSV files for customers, sales, exchange rates, and stores.  
- **Handling Missing Values**: Addressed missing data by filling null values appropriately.  
- **Data Type Conversion**: Converted columns to correct data types (e.g., dates, integers, floats).

**Step 2: Data Merging**  
- **Merging Datasets**: Combined all cleaned datasets into a unified DataFrame using Pandas' merge function with an inner join.

**Step 3: Data Upload to SQL**  
- **Connecting to SQL**: Established a connection to the SQL database via SQLAlchemy.  
- **Pushing Data**: Uploaded the cleaned and merged DataFrame to a database named `capstone`.

**Step 4: Data Analysis in SQL**  
- **Writing SQL Queries**: Developed SQL queries to analyze the data related to customers, sales, products, and stores.

**Step 5: Data Visualization with Power BI**  
- **Uploading Queries**: Imported the SQL query results into Power BI.  
- **Creating Visualizations**: Designed visualizations to showcase key insights from the analysis.