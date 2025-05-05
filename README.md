# Chapter 1: Data Collection
- **Extract Data from MySQL**: Connect to MySQL, list tables, and retrieve data using SQLAlchemy.
- **Extract Conversion Rates from API**: Call API for conversion rates and clean the data.
- **Merge Data**: Combine transaction, customer, product, and conversion rate data.
- **Save to Parquet**: Export the merged data as Parquet files.

# Chapter 2: Data Cleansing with Apache Spark
- **Install Spark**: Set up Apache Spark and PySpark.
- **Data Profiling**: Analyze dataset structure, types, and missing values.
- **Exploratory Data Analysis**: Visualize data distributions and trends.
- **Data Cleansing**: Handle missing values, correct anomalies, and identify outliers.
- **Save Cleaned Data**: Export the cleaned data to Parquet.

# Chapter 3: Cloud Computing (Data Lake)
- **Upload/Download Files**: Use Python SDK to upload and download files to/from Google Cloud Storage (GCS).

# Chapter 4: Data Pipeline Orchestration
- **Airflow Tasks**: Set up Airflow tasks for MySQL data retrieval, API calls, and data merging.
- **Set Dependencies**: Ensure tasks run in order by defining dependencies.

# Chapter 5: Data Warehouse
- **Load Data via BashOperator**: Use `bq load` to load data from GCS to BigQuery.
- **Load Data via GCSToBigQueryOperator**: Use Airflow’s `GCSToBigQueryOperator` for seamless BigQuery integration.

# Chapter 6: Data Visualisation
- **Create View**: Filter and convert data in BigQuery for reporting.
- **Upload to Looker Studio**: Visualize data from BigQuery in Looker Studio.
- **Sales Dashboard**: Create a dashboard showing sales performance.
- **Customer Insights**: Build a dashboard to show customer insights.
