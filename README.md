# **Overview** ##
Microsoft has decided to create a new movie studio and require more insight into which types of films are doing best at the box office. 
This project uses descriptive statistical analysis on data gathered from IMDb website to gain insight on which movies are most popular. 
Two seperate datasets were used for this analysis to gain insight into the top 5 most and least rated movies, Also looked into movies that brought more domestic gross sales,From the data collected and analyzed, I recommend Microsoft to produce Eden, Truth and Dare, Legend, The Void and Paranoia.
More emphaisze in production of Truth and Dare which is the most second most popular movie but fetches more Domestic Gross than the other 5.

## **Business Understanding** ##
Microsoft wants to produce movies that are going to be successful in order to make profits, they want to know which types of movies are the
most successful. To answer that question Domestic gross data was analysed to see the most financially successful movies,
along with frequeny given and number of votes for each type. To check popularity with the financila gains it brings to tah table

## **Data Understanding** ##

#We first import all the libraries that will be used in the notebook.
#Importing the libraries
import pandas as pd
import csv
import json
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns

## **Data Analysis** ##
The data analysed came from IMDb website. IMDb (Internet Movie Database) is an online database of
infomation relating to all movies, television programs, video games and streaming content online. I used 2 files from IMDb;tmdb.movies.csv and bom.movie_gross.csv to answer the question of which movies were most successful, mainly focusing on the Domestic Gross sales income along with the most popular movie and number of votes received.

The columns in the bom.movie_gross.csv data were; 
title	
studio	
domestic_gross	
foreign_gross	
year

The columns in the tmdb.movies.csv were
genre_ids	
id	
original_language	
original_title	
popularity	
release_date	
title	
vote_average	
vote_count

After checking the information on each table to see column names and null values, I joined the two datasets, df1 and df2 together using the 'title' column as it was a unique identifier creating a new dataframe called merged_df1_df2.

Handled all the missing values by filling them with the mode of the data and checked not to have the duplicates.

![alt text](image.png)The top 5 most popular movies were: 
Eden
Truth or Dare
Legend
The Void 
Paranoia

![alt text](image-1.png)The bottom 5 least popular movies are:
Welcome to Me
Big Stone Gap
Lincoln
The Descendants
The Lovers and the Despot

![alt text](image-2.png)The most popular movie that would bring more Domestic Gross is Truth or Dare

#Conclusion and Recommendation

From the data collected and analyzed, we can conclude that.
- Most people prefer to watch Eden, Truth and Dare, Legend, The Void and Paranoia
- As much as Eden is the most popular movie, it's income gross is less. 
- Truth and Dare is second most popular movie and fetches more Domestic Gross than the rest top 5

#Next Steps.
- We should consider the age range from which this statistics were collected.
- Also we can check the prefererd day and time of the week people watch movies

#Thank You
phoebewawire@moringaschool.com
Linkedln; CCOP Phoebe Wawire