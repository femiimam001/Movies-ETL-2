# Movies-ETL-2

In this project, we shall be analysing a company called **Amazing prime Video**. They are platform for streaming movies and TV shows.One of the world largest online retailer. The amazing prime video team would like to develop an algorithm to predict which of their movies released will become more popular. In other to inspire the team, have some fun and connect with the local coding community, amazing prime has decided to sponsor an hackerthon, providing a clean data set of movie data, and asking participants to predict the popular pictures.

Breda a member of the amazing prime video team, has been task with the creating data sets for the harkerthon. There are two data sources, a scrable wikipedia for all movies released since 1990 and rating data from the movie lands website. She would need to **extract** the data from the _two_ **_sources_** , **transform** it into _one_ clean data set and finally load that data set into a **SQL table** .
Results
Write an ETL function to read three data files
The function takes the Wikipedia JSON, the Kaggle metadata and MovieLens csv files and creates three separate DataFrames.

Extract and Transform the Wikipedia data
We filtered out the TV shows, consolidated the redundant data, removed the duplicates and formatted the Wikipedia data.

Extract and Transform the Kaggle and rating data
Again, we consolidated the redundant data, removed the duplicates, formatted and grouped the data.
The Kaggle and rating data were then merged with the Wikipedia movies DataFrame.

Load the data to a PostgreSQL Movie Database
