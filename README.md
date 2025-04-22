
# Chapter 1: Data Collection

This chapter focuses on collecting data from both a MySQL database and a public API, followed by merging, transforming, and exporting the data to CSV and Parquet formats.

## Main Steps

1. Extract data from MySQL using SQLAlchemy and PyMySQL
2. Load data into Pandas DataFrames
3. Extract conversion rate data via a public REST API
4. Merge transaction, product, customer, and conversion rate data
5. Create calculated fields like total_amount and thb_amount
6. Clean and rename columns for consistency
7. Export the final dataset to CSV and Parquet formats
