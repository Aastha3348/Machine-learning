# Hierarchical clustering
This file explains about the Hierarchial Clustering Algorithm and contains the source code of the algorithm.
## Here's what you need to know about Hierarchial Clustering
  - Hierarchical clustering, also known as hierarchical cluster analysis, is an algorithm that groups similar objects into groups called clusters.
  - <B> Hierarchial Clustering </B> is used to build a hierarchy of clusters where each node of a Cluster consists of the Clusters of its Daughter nodes.
## Strategies applied for Hierarchical clustering

  * ### <B> Divisive Approach </B> <br>
  Also known as  <B> Top-Down Approach </B> . <br>
  It starts with observations in a custer and breaks it down into smaller pieces. <br>
  Divisive clustering is good at identifying large clusters. <br>
  
  ### Steps involved in Divisive Hierarchical clustering
    Step 1. Include all the data points in a single large cluster.
    Step 2.  Divide the most heterogeneous cluster into two.
    Step 3. Iterate the process until all data points are in their own cluster.
  
  * ### <B> Agglomerative Approach </B> <br>
  Also known as <B> Bottom-Up Approach </B> . <br>
  Each observation starts in its own cluster and pairs of clusters are merged together as they move up the hierarchy. <br>
  Agglomerative clustering is good at identifying small clusters. <br>
  
   ### Steps involved in Agglomerative Hierarchical clustering
    Step 1. Create n clusters, one for each data points.
    Step 2. Compute the distance proximity matrix. 
    Step 3. Repeat the following steps 
            - Merge the two closest clusters.
            - Update the matrix
    Step 4. Stop if only one cluster is remaining.
    
## Distance between Clusters
  1. <B> Single Linkage Clustering </B>   - Minimum distance between clusters.
  2. <B> Maximum Linkage Clustering </B>  - Maximum distance between clusters.
  3. <B> Average Linkage Clustering </B>  - Average distance between clusters.
  4. <B> Centroid Linkage Clustering </B> - Distance between cluster centroids.
 
 ## Advantages of Hierarchical clustering
   - Doesn't require number of clusters to be specified.
   - Easy to implement
