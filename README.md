# Basic_ETL_pipeline
This is a very simple ETL pipeline demonstration that I learned from the "Data Engineering Foundations" course on LinkedIn Learning. It extracts data using PySpark 
from a postgresql database (containing two tables, 'movies' and 'users') using the PySpark framework, aggregates (transforms) the data (as per requirements for 
an OLAP database, to allow analytics), and loads the transformed data into the DB as a new table (avg_ratings). 
