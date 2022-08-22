# Movies-ETL
## Overview of the project 
The purpose of the project is to do ETL process and prepare a clean data for analysis, for Amazing Prime Hackathon. Wikipedia data, Kaggle metadata and the MovieLens rating data were extracted , transformed and loaded into SQL database for the analysis. 
For this ETL analysis challenge, 
* An ETL function was created to read three data files, Wikipedia data, Kaggle metadata and the MovieLens rating data.
* Wikipedia data was extracted and transformed.
* Kaggle and rating data were extracted and transformed.
* Movie database was created and loaded in Postgre SQL.

## Results
1.ETL function for Wikipedia data, Kaggle metadata and the MovieLens rating data.

![image](https://user-images.githubusercontent.com/108298416/185820159-e56a2b35-f653-4001-9469-0dc29b37f6c2.png)

![image](https://user-images.githubusercontent.com/108298416/185820199-d9e69990-f715-420d-8a9c-cfc2f70692e3.png)

![image](https://user-images.githubusercontent.com/108298416/185820271-05d46d6c-d946-4258-9d57-bdc8c82a7fb0.png)


2.Extracted and Transformed Wikipedia Data

![image](https://user-images.githubusercontent.com/108298416/185820344-7c8ef87a-e4fb-4ff6-84fa-40fddc12fe79.png)

3.Extracted and Transformed Kaggle and Rating Data

![image](https://user-images.githubusercontent.com/108298416/185820452-970161ca-5f3f-40c0-b24d-da86e7f1c4ac.png)

![image](https://user-images.githubusercontent.com/108298416/185820491-e3a47954-0a35-4556-aed1-474154323e90.png)

4.Ratings and movie table rows count after data was loaded in PostgreSQL movie database

![movies_query](https://user-images.githubusercontent.com/108298416/185820629-781a22de-bd83-454a-9cde-cce2d651032c.PNG)

![ratings_query](https://user-images.githubusercontent.com/108298416/185820635-9732149b-65c6-4e81-b96e-f9003fd950df.PNG)

## Summary
The ETL function was created by collecting movie data from different sources (Wikipedia JSON and Kaggle and ratings csv files) and cleaned. The cleaned data was then transformed and loaded as two different tables movies and ratings csv files for the hackathon participants for the further analysis.
