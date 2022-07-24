# :clapper: Movies-ETL :movie_camera:

## Purpose :film_strip:

1)  To create one function that takes in the [three files](https://github.com/Super-Manda/Movies-ETL/blob/main/Data%20Sources.zip)
  - Wikipedia data
  - Kaggle metadata
  - MovieLens rating data
  
    - (Files that are too large come from [here](https://www.kaggle.com/account/login?titleType=dataset-downloads&showDatasetDownloadSkip=False&messageId=datasetsWelcome&returnUrl=%2Fdatasets%2Frounakbanik%2Fthe-movies-dataset%3Fresource%3Ddownload) )

2)  To perform the extract, transform, and load (ETL) process by adding the data to a PostgreSQL database.


## Load
![Loading](https://github.com/Super-Manda/Movies-ETL/blob/main/elapsed%20time%20to%20add%20the%20data%20to%20the%20database.png)


## End Products in SQL

### Movies Query
![movies_query](https://github.com/Super-Manda/Movies-ETL/blob/main/movies_query.png)

### Ratings Query
![ratings_query](https://github.com/Super-Manda/Movies-ETL/blob/main/ratings_query.png)


- **These end products match what was loaded in the "loading phase (see highlighting above)."**

