# Udacity_Data_Eng_Pro
Udacity Final Project

The objective of this project is to create a SQL analytics database for a fictional music streaming service called Sparkify. Sparkify's analytics team seeks to understand what, when and how users are playing songs on the company's music app. The analysts need an easy way to query and analyze the songplay data, which is currently stored in raw JSON logs and metadata files on a local directory.

As the data engineer assigned to the project, I have implemented an ETL pipeline in python to process and upload the data into a PostgreSQL database. The ETL process extracts each songplay from the list of page actions recorded by the app. Data for analysis, such as song name, user information, subscription tier, and location of user, is structured into the main songplay table and related dimensional tables.

Data Modeling with Postgres was submitted for Udacity's Data Engineering Nanodegree (DEND) in Spring 2019.
