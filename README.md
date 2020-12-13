# Movies-ETL

## Project Overview

In this module, we learned how to use the Extract, Transform, Load (ETL) process to create data pipelines. A data pipeline moves data from a source to a destination, and the ETL process creates data pipelines that also transform the data along the way. 

## Resources

The Movies-ETL uses Kaggle data. The Kaggle dataset pulls from the MovieLens dataset of over 20 million reviews and contains a metadata file with details about the movies from The Movie Database (TMDb). There, we downloaded the zip file from Kaggle, extracted, and decompressed the CSV files we were interested in; movies_metadata.csv and ratings.csv files.

* Data Source: wikipedia-movies.json, movies_metadata.csv, ratings.csv
* Software: Python, Pandas, PostgreSQL

## Challenge Objectives

* Create an automated ETL pipeline.
* Extract data from multiple sources.
* Clean and transform the data automatically using Pandas and regular expressions.
* Load new data into PostgreSQL.

## Sneakpeak to SQL Uploaded Data

We checked that the function works correctly on the current Wikipedia and Kaggle data using pgAdmin by verifing the columns have the correct data type, inspecting the first 100 rows, and checking the row count.

![1](https://user-images.githubusercontent.com/73450637/102001607-fe6f6500-3cc1-11eb-82a6-e9e90c6efe2f.png)


