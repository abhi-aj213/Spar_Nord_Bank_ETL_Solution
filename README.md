# Spar_Nord_Bank_ETL_Solution
Batch Data Processing and ETL project using Apache Sqoop, Apache Spark, and Amazon Redshift

Problem Statement
Spar Nord Bank is trying to observe the ATM withdrawal behavior and the corresponding dependent factors to optimally manage the refill frequency across Denmark. Apart from this, other insights also have to be drawn from the data.

Broadly we will be performing the following tasks:
Extracting the transactional data from a given MySQL RDS server to HDFS(EC2) instance using Sqoop.

Transforming the transactional data according to the given target schema using PySpark.

This transformed data is to be loaded to an S3 bucket.

Creating the Redshift tables according to the given schema.

Loading the data from Amazon S3 to Redshift tables.

Performing the analysis queries.

Analytics
Coming to the analysis part, we will carry out the calculations to perform the following analytical queries:

Top 10 ATMs where most transactions are in the ’inactive’ state

Number of ATM failures corresponding to the different weather conditions recorded at the time of the transactions

Top 10 ATMs with the most number of transactions throughout the year

Number of overall ATM transactions going inactive per month for each month

Top 10 ATMs with the highest total amount withdrawn throughout the year

Number of failed ATM transactions across various card types
