# Big-data-ETL: Amazon_Vine_Analysis 

## Background

In this assignment you will put your ETL skills to the test. Many of Amazon's shoppers depend on product reviews to make a purchase. Amazon makes these datasets publicly available. However, they are quite large and can exceed the capacity of local machines to handle. One dataset alone contains over 1.5 million rows; with over 40 datasets, this can be quite taxing on the average local computer. Your first goal for this assignment will be to perform the ETL process completely in the cloud and upload a DataFrame to an RDS instance. The second goal will be to use PySpark or SQL to perform a statistical analysis of selected data.
There are two levels to this homework assignment. The second level is optional but highly recommended.



## Project objective

Create DataFrames to match production-ready tables from two big Amazon customer review datasets.
Analyze whether reviews from Amazon's Vine program are trustworthy. Moreover, how to deploy google Colaboratory Notebook files for ETL pipeline of Amazon music reviews to AWS PostgreSQL database and analysis of the ratio of five star reviews as it relates to participation in the Vine program.

## Resources

- Data Source
  - [Amazon-reviews-links](https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt)
  - [Music data](https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Music_v1_00.tsv.gz)

- Technologies used
  - Python
  - Spark 
  - PySpark
  - PostgreSQL 
  - pgAdmin
  - [Google colaboratory](https://colab.research.google.com/notebooks/welcome.ipynb)
  
# Results
Running AWS RDS ETL Pipeline Amazon_Music_Reviews.ipynb to populate the four tables in our PostgreSQL database as shown in the following images:

- review_id_table
- products
- customers
- vine_table
