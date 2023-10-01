# Customer_segmentation_clustring
This repository contains an implementation of customer segmentation using the K-means clustering algorithm. Customer segmentation is a crucial strategy for businesses to understand their customer base better, target specific groups with tailored marketing strategies, and enhance overall customer satisfaction.
We will be using unsupervised learning in this project .

A.)Introduction to Unsupervised learning 
It involves training of machine using information that is neither classified nor labelled and allowing the algorithm to act on that information without guidance.
TYPES: Association, Clustering 
Unlike supervised learning , unsupervised learning methods cannot be directly applied to regression or classification problem because u have no idea what the values or output data look like. Hence making it difficult to train the algorithm the way you normally put. Here the task of machine to group unsorted information according to similarities ,patterns and differences without any priority reading data .unlike supervised learning no teacher is provided that means no training will be given to machine therefore the machine is restricted to find the hidden structure in unlabelled data by itself .
 Unsupervised learning can categorised into two types: Association, Clustering 
Association: 
An association rule learning problem is were you want to discover rules that describes large portion of your data such as people that by x also tend to y. 
Clustering :
A clustering problem is were you want to discover the Inherent grouping in the data such as grouping customers by grouping behaviour. Clustering may include types like hierarchal clustering ,k- means clustering , principle component analysis , singular value decomposition or independent component analysis .

B.)K-means Algorithm -
It is an iterative algorithm that divides the unlabelled dataset into k different clusters in such a way that each dataset belongs only group that has similar properties.
It is an iterative algorithm that tries to partition the dataset into k predefined distinct non overlapping sub groups where each data point belongs to only one group .It tries to make intra cluster data points as similar as possible while also keeps the clusters as different as possible . It assigns data points clusters such that the sum of their distances between the data points and the cluster centroid is at the minimum. The least variation we have within the clusters the more homogeneous data points are within the same cluster.
How should you choose the optimum number of clusters so there are 2 possible ways of choosing the number of clusters 
a.) Elbow Method : here you draw above between wss that is Within sum of squares and the no. of clusters . It is called the Elbow method because the curve looks like a human arm and elbow point gives us the optimum no. of clusters . You should take the elbow point as the final no. of clusters.
b.) Purpose Based : You can run k-means clustering algorithm to get different clusters based on variety of purposes. You can partition the data on different matrix and see how well it performs for particular case . Let take an example of marketing t-shirts of different sizes , you can partition the dataset into different number of clusters depending upon purpose that you want to meet.
