# Movies-ETL

## Overview of the Analysis

For this analysis we received movie data from three sources and needed to transform the data into a single data deliverable. The data came from multiple sources including data that was scraped from the web. The data quality varied and was, in some cases, duplicated in the various sources.

During the analysis it was necessary to review the different attributes, determine what to do with it, in some cases it was kept, in some cases it was dropped and in some cases it was replaced. 

The end result was claned data that was loaded into a SQL database so it could be used for a hackathon.


### Data Sources and Software
The following data files were provided:
 - movies_metadata.csv
 - ratings.csv
 - wikipedia-movies.json 


The analysis was conducted using Pandas, PostgreSQL 11 and pgAdmin 4


