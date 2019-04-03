# spark-ML
use ML with spark

## movie recommendation with mllib in PySpark
- https://github.com/nocwang/spark-ML/blob/master/BigData/Recommender/recommender.py

- Collaborative filtering is commonly used for recommender systems. These techniques aim to fill in the missing entries of a user-item association matrix, in our case, the user-movie rating matrix. MLlib (pyspark.mllib.recommendation) currently supports model-based collaborative filtering, in which users and products are described by a small set of latent factors that can be used to predict missing entries. In particular, we implement the alternating least squares (ALS) algorithm to learn these latent factors.

## KMeans clustering in PySpark
- https://github.com/nocwang/spark-ML/blob/master/BigData/Clustering/clustering.py
- Clustering is an unsupervised learning problem whereby we aim to group subsets of entities with one another based on some notion of similarity. Clustering is often used for exploratory analysis and/or as a component of a hierarchical supervised learning pipeline (in which distinct classifiers or regression models are trained for each cluster).

## Image Classification with MNIST Dataset
- https://github.com/nocwang/spark-ML/blob/master/BigData/MNIST/CNN.py
- The MNIST database (Modified National Institute of Standards and Technology database) is a large database of handwritten digits that is commonly used for training various image processing systems. The database is also widely used for training and testing in the field of machine learning.
