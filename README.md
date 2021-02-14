# Movies-ETL

## Overview of Project
### Purpose

Amazing Prime, the world’s largest streaming platform, wants to develop an algorithm which determines what type of low-budget movies will become popular with viewers in the future so they can buy the streaming rights before the competition can. To carry out this analysis, a database of current movies and their audience ratings needs to be constructed. Britta, an analyst for Amazing Prime, has been tasked with performing an ETL (Extract, Transform, and Load) process to develop this database. Britta will extract the raw movie data from Wikipedia and the raw ratings data from MovieLens, transform it to arrive at a clean, high-level summary, and, finally, load it into a SQL database. To streamline the data pipeline, Britta will create a Python function to automate the ETL process for future usage.

With the completion of the ETL process, Brita was able to create a Movies data table in SQL which contains 6,052 rows of movie data and Ratings data table that contains 26,024,289 rows of ratings data:

<img src ="https://github.com/Jafranco96/Movies-ETL./blob/main/Resources/movies_query.png">

<img src ="https://github.com/Jafranco96/Movies-ETL./blob/main/Resources/ratings_query.PNG">


With these tables, Amazing Prime now has the foundational element to develop the algorithm from.
