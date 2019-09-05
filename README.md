# Netflix Movie Recommendation System


## Problem Statement

Recommender system is about connecting people to products they love. 
The goal of my project is to create movie recommender system based on Netflix data

![alt text](https://github.com/achernyshova/Movie-Recommender-System/blob/master/images/woman.jpeg)

## Dataset
The Netflix Prize was an open competition for the best algorithm to predict user ratings for films, based on previous ratings without any other information about the users or films, i.e. without the users or the films being identified except by numbers assigned for the contest. 
Datasets were taken from https://www.kaggle.com/netflix-inc/netflix-prize-data and https://www.kaggle.com/rounakbanik/the-movies-dataset/home

There are 17 770 unique movie IDs. <br>
There are 480 189 unique user IDs. <br>
There are ratings. Ratings are on a five star (integral) scale from 1 to 5. <br>
Metadata of 44 500 movies

 ### Data dictionary
 | Column        | Type | Description                                              |
|---------------|-----------|----------------------------------------------------------|
| movie_id    | int   | unique identifier of movie    |
| user_id   | int   | unique identifier of user                  |
| rating | int    | rating was given to a movie by a user (scale 1-5) |
| date | datetime   | date when rating was given to a movie by a user |



## Executive Summary
The project will do the following parts:
1. Load Data
2. Cleaning data
2. Doing an EDA
3. Theory of Recommendation Systems
4. Modeling 
5. Conclusions


## Conclusions and findings
I trained 4 types of models: 
- KNN
- SVDpp
- Deep Learning
- Deep Learning with Metadata

SVDpp showed the best result.
In practice, companies should make choices based on multiple factors like accuracy, complexity and business impact, under realistic constraints on resources.


## Next steps
Further improvements for the model includes:
- Improve deep learning approach
- Use Sage Maker
