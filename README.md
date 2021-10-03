# Movies_ETL

## Overview

### Purpose
>Amazing Prime loves the dataset and wants to keep it updated on a daily basis. Britta needs your help to create an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. You’ll need to refactor the code from this module to create one function that takes in the three files—Wikipedia data, Kaggle metadata, and the MovieLens rating data—and performs the ETL process by adding the data to a PostgreSQL database

### Resources
- Language: Python 3.7.10, SQL
- Interface: Jupyter Notebook, pgAdmin 4
- Environment: Miniconda
- Packages: Pandas, Numpy, JSON, re (Regex), SQLAlchemy, Psycopg2, Time

## Results

### Deliverable 1
Write an ETL Function to read three data files. Output of all 3 converted to DataFrames.

![d1-kaggle](https://github.com/li-emily/Movies_ETL/blob/main/Resources/d1_kaggle_metadata.png)

![d1-wiki](https://github.com/li-emily/Movies_ETL/blob/main/Resources/d1_wiki_movies_df.png)

![d1-ratings](https://github.com/li-emily/Movies_ETL/blob/main/Resources/d1_ratings.png)


### Deliverable 2
Extract and transform the Wikipedia data.

![d2-wiki](https://github.com/li-emily/Movies_ETL/blob/main/Resources/d2_wiki_movies_df.png)

![d2-wiki-col](https://github.com/li-emily/Movies_ETL/blob/main/Resources/d2_wiki_movies_columns.png)

### Deliverable 3
Extract and transform the Kaggle data.

![d3-movies](https://github.com/li-emily/Movies_ETL/blob/main/Resources/d3_movies_df.png)

![d3-movie-rate](https://github.com/li-emily/Movies_ETL/blob/main/Resources/d3_movies_w_ratings.png)

### Deliverable 4
Create the Movie Database and load data into PostgreSQL. Output count of movies and ratings tables to confirm all rows have been copied over.

![movies_query](https://github.com/li-emily/Movies_ETL/blob/main/Resources/movies_query.png)

![ratings_query](https://github.com/li-emily/Movies_ETL/blob/main/Resources/ratings_query.png)

