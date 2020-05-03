# Recommender System Project

The recommendation dataset used here is from a collection called MovieLens, which contains users' movie ratings and is popular for implementing and testing recommender systems. The specific dataset we will be using for this lab is MovieLens 100K Dataset which contains 100,000 movie ratings from 943 users and a selection of 1682 movies.

The notebook explores three different similarity metrics in cosine, eucledian and jaccard. The algorithms used to make recommendation are as follows:
1. User Average
2. Popularity
3. Collaborative Filtering (User-User and Item-Item)
4. Probabilistic Matrix Factorization (PMF)

The different algorithms are compared by metrics such as RMSE, Precision@K, Recall@K after cross-validation. The Collaborative Filtering algorithm (Item-Item) is also used to make movie recommndation. What should you watch if you liked Men in Black? Only one way to find out.
