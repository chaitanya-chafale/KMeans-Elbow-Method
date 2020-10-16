**Hello Greeks !**

**Introduction**

This project uses the CGPA.csv file as the dataset (provides cgpa of the students) and uses kmeans algorithm to cluster the points using the elbow point method .

This project contains 2 files :

1.) Kmeans 1-cgpa (jupyter notebook file) :- Contains the python code .

2.) CGPA (csv file) :- Contains the dataset which the kmeans algo uses .

Note :- Download these two file and make sure to change the "file_location" variable in the step (2) of the code according .

**BASIC KNOWLEDGE**

*What is Kmeans clustering algorithm ?*

Kmeans algorithm is an iterative algorithm that tries to partition the dataset into Kpre-defined distinct non-overlapping subgroups (clusters) where each data point belongs to only one group.
It assigns data points to a cluster such that the sum of the squared distance between the data points and the cluster’s centroid (arithmetic mean of all the data points that belong to that cluster) is at the minimum. The less variation we have within clusters, the more homogeneous (similar) the data points are within the same cluster.

*How to find the optimal value of cluster(i.e is k) ?*

Elbow method is one of the metric that give intuition about k value .It gives us an idea on what a good k number of clusters would be based on the sum of squared distance (SSE) between data points and their assigned clusters’ centroids. We pick k at the spot where SSE starts to flatten out and forming an elbow. 

**APPLICATION**

1.) Get a meaningful intuition of the structure of the data we’re dealing with.

2.)Cluster-then-predict where different models will be built for different subgroups if we believe there is a wide variation in the behaviors of different subgroups. An example of that is clustering patients into different subgroups and build a model for each subgroup to predict the probability of the risk of having heart attack.
