# Introduction
A startup called Sparkify wants to analyze the data they've been collecting on songs and user activity on their new music streaming app. The analytics team is particularly interested in understanding what songs users are listening to. Currently, they don't have an easy way to query their data, which resides in a directory of JSON logs on user activity on the app, as well as a directory with JSON metadata on the songs in their app.

They'd like a data engineer to create a Postgres database with tables designed to optimize queries on song play analysis, and bring you on the project. Your role is to create a database schema and ETL pipeline for this analysis. You'll be able to test your database and ETL pipeline by running queries given to you by the analytics team from Sparkify and compare your results with their expected results.


## Project Description
In this project, you'll apply what you've learned on data modeling with Postgres and build an ETL pipeline using Python. To complete the project, you will need to define fact and dimension tables for a star schema for a particular analytic focus, and write an ETL pipeline that transfers data from files in two local directories into these tables in Postgres using Python and SQL.

### STAR Schema analysis 

> Fact Table is the songplays - which is the records in log data associated with songs plays.
> Dimention Tables is : users,songs,artists and time

## Project Files 
This workspace consists : 
- sql_quieries.py - contains all your sql quieries for : drop and create tables.
- create_table.py - drops and create your tables [used to reset your db before ETL]
- test.ipynb - displays the first few rows of each table to let you check your database.
- etl.ipynb - reads and processes a single file from song_data and log_data and loads the data into your tables. 
- etl.py - reads and processes files from song_data and log_data and loads them into your tables. You can fill this out based on your work in the ETL notebook.
- README.md provides discussion on your project.
