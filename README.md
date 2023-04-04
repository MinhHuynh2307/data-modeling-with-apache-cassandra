# Data Modeling With Apache Cassandra

## 1. Project description
A startup called Sparkify wants to analyze the data they've been collecting on songs and user activity on their new music streaming app. The analysis team is particularly interested in understanding what songs users are listening to. Currently, there is no easy way to query the data to generate the results, since the data reside in a directory of CSV files on user activity on the app.

As a data engineer, I am going to create an Apache Cassandra database which can create queries on song play data to answer the questions. The database will be tested by running queries given by the analytics team from Sparkify to create the results.

In this project, I will model data by creating tables in Apache Cassandra to run queries. The ETL pipeline will be designed to transfer data from a set of CSV files within a directory to create a streamlined CSV file to model and insert data into Apache Cassandra tables.

## 2. Directories and Files

**`data-modeling-apache-cassandra.ipynb`** This notebook describes **02 PARTS** of the project.
- PART I: ETL Pipeline for Pre-Processing the Files
- PART II: Complete the Apache Cassandra coding portion of the project.
 
**`event_datafile_new.csv`** This csv file contains data resulted from pre-processing ETL pipeline and will be used to insert data into the Apache Cassandra tables.

**`images`** This directory contains a screenshot of what the denormalized data should appear like in the event_datafile_new.csv after running the pre-processing ETL pipeline:

**`event_data`** The directory of CSV files partitioned by date

