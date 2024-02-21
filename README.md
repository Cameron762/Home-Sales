# Home-Sales
# Analysis of Home Sales Data with Spark SQL

### Introduction
#### This Jupyter Notebook explores and analyzes home sales data using SparkSQL. The dataset contains information about home sales, including features like the number of bedrooms, bathrooms, square footage. The analysis aims to derive insights into home prices based on various criteria.

### Prerequisites
- #### Apache Spark
- #### Jupyter Notebook
- #### Python

### File Structure
- #### home_sales_revised.csv: CSV file containing the raw home sales data.
- #### Home_Sales.ipynb: Jupyter Notebook containing the Spark SQL analysis.

### Analysis Steps
- #### Data Loading: The raw CSV data is loaded into a Spark DataFrame.
- #### Data Preparation: The DataFrame is preprocessed and temporary views are created.
- #### Analysis Queries: Various Spark SQL queries are executed to answer specific questions about home prices based on different criteria.
- #### Performance Evaluation: Run time of queries is measured, and caching and partitioning techniques are explored for optimization.

### Results
- #### Average home prices based on different criteria (e.g., number of bedrooms, bathrooms, view ratings).
- #### Comparison of query run times with and without caching and partitioning.

### Conclusion
#### The analysis provides insights into factors influencing home prices and demonstrates the performance impact of caching and partitioning in Spark SQL queries.
