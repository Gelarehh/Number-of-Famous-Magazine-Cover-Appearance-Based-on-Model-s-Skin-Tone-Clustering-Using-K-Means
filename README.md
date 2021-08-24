# K-Means-Clustering

The k-Means Clustering algorithm is one of the simplest and most popular algorithms used in data mining, especially in unsupervised learning.
Usually, in multi-feature mode, different properties of objects must be used to cluster them. In this way, we deal with multidimensional data. Some properties of objects may be quantitative and some qualitative. However, what is important is a way to measure the degree of similarity or dissimilarity between objects that should be considered in clustering methods. 
<br/><br/>

<p align="center">
  <img width="540" height="300" src="https://user-images.githubusercontent.com/66460485/130614414-99d9fb24-de9a-45b4-bc0c-51cadb0e74de.png">
</p>

In K-Means Clustering, optimization of an objective function is used. The clustering responses in this method may be performed with the help of minimization or maximization of the objective function. This means that if the criterion is distance measure between objects, the objective function will be based on minimization. The answer to the clustering operation is to find clusters where the distance between objects in each cluster is minimal. In contrast, if the dissimilarity function is used to measure the similarity of objects, the target function is selected so that the clustering response maximizes its value in each cluster.

The initialization method of the centroids in the implemented algorithm is k-means++, which selects initial cluster centers for k-mean clustering in a smart way to speed up convergence.

## Dataset
Simulations have been done on two different sets of data. First, a group of random nodes has been generated, and a clustering approach was done on them. To do so, four center points were determined in two-dimensional space, and 5000 nodes, including center nodes, were generated with a cluster deviation of 0.9. the data was splitted into four clusters.

For the second set, a .csv file containg dataset regarding ... was used as the data to be clustered. Here, the number of clusters is considered to be four and centroid values are calculated, too.
