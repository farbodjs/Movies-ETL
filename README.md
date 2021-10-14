# Movies-ETL
## Project Describtion
This project will create varous automated functions that takes in raw uncleaned data, from Wikipedia, Kaggle metadata and the MovieLens rating data.
Then it will perform ETL procedures (Extract, Transform, Load) to extract data from web, import CSV and Json files and subsequently performs various data cleaning techniques to transform the data from dirty to clean. final step will be loading the data into an existing PostgreSQL database.

## Methods of Procedure
For this analysis, we used the following breakdown:

1) write an ETL function to read three large data files,
2) extract and transform the Wikipedia data,
3) extract and transform the Kaggle and rating data,
4) load the data to a PostgreSQL Movie Database.

## Final Results
After performing Deliverable 4 (captured in ETL_Create_database.ipynb) we have (2) loaded tables : 1)ratings 2)movies which are ready for further analysis
## Tools
Python, Pandas, Matplotlib, Jupyter Notebook, pgAdmin Version 5.7, numpy, psycopg2, sqlalchemy and so forth

