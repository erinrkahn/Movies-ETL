# Movies-ETL

## Background

### Purpose

The purpose of this project was to create an automated pipeline that takes in new data, performs all approproiate transformations and then loads the data into existing tables. Three files were used; wikipedia.movies.json, movies_metadata.csv, ratings.csv. As part of the ETL process, these files were extracted from 2 sources, cleaned & joined, and then loaded into a SQL database. 

## Results

### Summary

To confirm the data was properly replaced in the SQL database, a query was run to confirm the row counts were correct. 

###### Movies Query
> ![movies_query](https://user-images.githubusercontent.com/77405273/112738644-f4483e00-8f21-11eb-9110-74a6df61ec98.png)

###### Ratings Query
>![ratings_query](https://user-images.githubusercontent.com/77405273/112738646-f6120180-8f21-11eb-9eab-cf667ddbcf07.png)
