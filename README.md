# :film_projector: Movies-ETL :tv:


## :bulb: Purpose  

1)  To create one function that takes in the [three files](https://github.com/Super-Manda/Movies-ETL/blob/main/Data%20Sources.zip)
  - Wikipedia data
  - Kaggle metadata
  - MovieLens rating data
  
    - (Files that are too large come from [here](https://www.kaggle.com/account/login?titleType=dataset-downloads&showDatasetDownloadSkip=False&messageId=datasetsWelcome&returnUrl=%2Fdatasets%2Frounakbanik%2Fthe-movies-dataset%3Fresource%3Ddownload) )

2)  To perform the extract, transform, and load (ETL) process by adding the data to a PostgreSQL database.


## :movie_camera: Extract and Transform 

### Read Three Data Files with a Written ETL function: 
- [Deliverable 1](https://github.com/Super-Manda/Movies-ETL/blob/main/ETL_function_test.ipynb)


### Extract and Transform the Wikipedia Data: 
- [Deliverable 2](https://github.com/Super-Manda/Movies-ETL/blob/main/ETL_clean_wiki_movies.ipynb)


### Extract and Transform the Kaggle data: 
- [Deliverable 3](https://github.com/Super-Manda/Movies-ETL/blob/main/ETL_clean_kaggle_data.ipynb) 


### Create the Movie Database: 
- [Deliverable 4](https://github.com/Super-Manda/Movies-ETL/blob/main/ETL_create_database.ipynb) 


## :film_strip: Load  	
![Loading](https://github.com/Super-Manda/Movies-ETL/blob/main/elapsed%20time%20to%20add%20the%20data%20to%20the%20database.png)


## :clapper: End Products in SQL

### Movies Query
![movies_query](https://github.com/Super-Manda/Movies-ETL/blob/main/movies_query.png)

### Ratings Query
![ratings_query](https://github.com/Super-Manda/Movies-ETL/blob/main/ratings_query.png)


- **These end products match what was loaded in the "loading phase (see highlighting above)."**

