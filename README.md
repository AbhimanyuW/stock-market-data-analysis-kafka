# Stock Market Data Analysis using Kafka

## Architecture 
<img src="Architecture.jpg">

## Description
The goal of this project was to create a data pipeline by utilising Apache Kafka. Firstly, the raw data present in a CSV format was emulated in the form of a data stream by using Python. Then, the Producer-Consumer model of Apache Kafka was set up to stream this data on an EC2 instance. This data was then stored onto an S3 bucket using Python. The next step was to build a Glue crawler to crawl this data and create a data catalog. Finally, Athena was utilised to run queries on this data. This completes a simple data pipeline.

## Technologies Used 
Python Programming Language

Amazon Web Services (AWS) - EC2, S3, Glue Crawler, Glue Catalog, Athena

Apache Kafka

## Dataset Used 
The dataset used was in a csv format and can be found here: https://github.com/AbhimanyuW/stock-market-data-analysis-kafka/blob/main/indexProcessed.csv

