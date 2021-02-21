# Movies_ETL

## Overview of Challenge
The challenge required students to create a cleaned up version of movies, movies with ratings and ratings datasets using the extract-transform-load (ETL) processes and place it within a function for easy updating. 

## Results
I have refactored the the ETL code from the module to create one function that takes in three files: Wikipedia data, Kaggle metadata, and the MovieLens rating data, and performs the ETL process by adding the data to my PostgreSQL database. With this refractored code, I have created an automated pipeline that takes in new data, performs the appropriate transformations, and loads the movie and ratings data into existing database tables. 
