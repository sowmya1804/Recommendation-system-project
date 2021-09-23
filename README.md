# Project Title: Book Recommendation System  

## Description  
Recommender systems are the systems that are designed to recommend things to the user based on many different factors. These systems predict the most likely product that the users are most likely to purchase and are of interest to. Companies like Netflix, Amazon, etc. use recommender systems to help their users to identify the correct product or movies for them.   
The recommender system deals with a large volume of information present by filtering the most important information based on the data provided by a user and other factors that take care of the user’s preference and interest. It finds out the match between user and item and imputes the similarities between users and items for recommendation.   
Both the users and the services provided have benefited from these kinds of systems. The quality and decision-making process has also improved through these kinds of systems.  

The data consists of three tables: ratings, books info, and users info.  
It contains 1.1 million ratings of 270,000 books by 90,000 users.   

Building A Book Recommender System – Recommendations based on rating count, Correlations, Collaborative Filtering Using k-Nearest Neighbors (kNN)  

## Getting Started
Tools used: Jupyter Notebook  
Languages: python  
Libraries: Numpy,Pandas,Matplotlib  
Dataset downloaded from kaggle- https://www.kaggle.com/rxsraghavagrawal/book-recommender-system  
files: Ratings,Users,Books  

## Table Of Contents  

1) Importing Libraries  
2) Reading the dataset with necessary features  
3) Understanding data  
4) Recommendations based on rating counts  
5) Recommendations based on correlations  
6) To ensure statistical significance, users with less than 200 ratings, and books with less than 100 ratings are excluded.  
7) Rating matrix  
8) Collaborative Filtering Using k-Nearest Neighbors (kNN)  
9) Filter to users in US and Canada only  
10) Cosine Similarity  
11) Implementing kNN  

Cosine Similarity: Cosine of the angle between the two vectors of the item, vectors of A and B is calculated for imputing similarity. If the vectors are closer, then small will be the angle and large will be the cosine.   
Collaborative Filtering:  
It is considered to be one of the very smart recommender systems that work on the similarity between different users and also items that are widely used as an e-commerce website and also online movie websites. It checks about the taste of similar users and does recommendations.   

## Conclusion:  
Recommendations can be done based on low cosine distance i.e., high similarity between the different users
