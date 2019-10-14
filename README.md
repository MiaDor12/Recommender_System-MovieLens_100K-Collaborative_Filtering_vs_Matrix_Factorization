# Recommender System - MovieLens 100K - Collaborative Filtering vs Matrix Factorization
* The notebooks contain implementations of recommander systems of two types: simple collaborative filtering vs matrix factorization.
* Collaborative filtering is an algorithm for recommendation, used for example to predict a user's rating of a movie. This is done by comparing the most similar users to the desired user, and the ratings they gave the desired movie.
* Matrix factorization is another algorithm for recommendation. This algorithm uses embedding to create two matrices, of the users and movies, such that their dot product gives the desired rating. 
* The data I used for this project is the MovieLens 100k, from GroupLens: https://grouplens.org/datasets/movielens/100k/
* In the full data set there are 100000 ratings by 943 users on 1682 movies, where each user has rated at least 20 movies.

For a better view of the notebooks:
* Simple collaborative filtering from scratch: https://nbviewer.jupyter.org/github/MiaDor12/Recommender_System-MovieLens_100K-Collaborative_Filtering_vs_Matrix_Factorization/blob/master/Collaborative_Filtering_from_Scratch.ipynb
* Matrix factorization:
