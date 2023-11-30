# Crowdfunding_ETL
Project 2 -- UC Berkeley Data Analysis Bootcamp

In this project, I started with two raw datasets with the information of crowdfunding ventures and the contact
info for the people who backed the projects, with the goal being to use the ETL (Extract, Transform, Load)
process to ultimately make this raw data useable in a Postgres database.\
\
Python was used to extract the raw data from the Excel files and also to transform the data into their own
separate CSV files.  From there, I created an ERD to map out the Postgres database, and created the schema/tables
that I would ultimately import the CSVs we created in Python to.

References\
Replacing header - https://stackoverflow.com/questions/31328861/replacing-header-with-top-row
