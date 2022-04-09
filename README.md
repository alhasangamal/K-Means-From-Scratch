# K-Means-From-Scratch
K-Means Clustering is an unsupervised learning algorithm that aims to group the observations in a given dataset into clusters. The number of clusters is provided as an input. It forms the clusters by minimizing the sum of the distance of points from their respective cluster centroids.



Steps of K-means

1- Decide how many clusters you want, i.e. choose k

2- Randomly assign a centroid to each of the k clusters

3- Calculate the distance of all observations to each of the k centroids

4- Assign observations to the closest centroid

5- Find the new location of the centroid by taking the mean of all the observations in each cluster

6- Repeat steps 3-5 until the centroids do not change position



In this exercise, we will work with a hypothetical dataset generated using random values. The distinction between the groups is made by shifting the first part of the dataset a bit higher in the feature space while shifting the second part a bit lower. This will create two more or less distinguishable groups.
