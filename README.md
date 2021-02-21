# Movies_ETL

## Overview of Challenge
Created a cleaned up version of movies, movies with ratings and ratings datasets using the extract-transform-load processes. The challenge task was to take the ETL code and place it within a function to be able to update the database files on a daily basis. I created an automated pipeline that takes in new data, performs the appropriate transformations, and loads the movie and ratings data into existing tables. 

## Results
I have refactored the the ETL code from the module to create one function that takes in three files: Wikipedia data, Kaggle metadata, and the MovieLens rating data, and performs the ETL process by adding the data to my PostgreSQL database.
