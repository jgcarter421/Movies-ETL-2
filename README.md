# Movies ETL (Extract, Transform, Load)

## Overview
Amazing Prime conducted a Hackathon event and loved the dataset from this module and wants to update it on a daily basis.  My friend Britta needed my help to create an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables.  For this project, I had to refactor the code from this module to create one function that takes in the three files - Wikipedia data, Kaggle metadata, and the MovieLens rating data — and performs the ETL process by adding the data to a PostgreSQL database.  This module had the following deliverables:
* Write an ETL function that reads the three data files.
* Extract and transform the Wikipedia data.
* Extract and transform the Kaggle data.
* Create the Movies Database.

## Summary
The ETL function collects and cleans the movie data from the three different sources.  It transforms the data and loads it into two separate PostgreSQL tables for future analysis.
