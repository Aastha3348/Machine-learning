This File constains the K Means Source code that I worked on and explains about the algorithm. 
I've also tried to implement <B> Hierarchial clustering </B> using the same data and with the help of few additional steps. 
## Here's what you need to know about K-Means
  - <B> K-means clustering </B> is one of the simplest and popular unsupervised machine learning algorithms. 
  - To achieve this objective, K-means looks for a fixed number (k) of clusters in a dataset. 
  - K Means divides the data into non-overlapping subsets without any cluster internal structure , or labels.
  - A <B> Cluster </B> refers to a collection of Data points aggregated together because of certain similarities.
  - Basically, In the process of clustering, one can identify which observations are alike and classify them significantly in that manner. 
  - One of the most important features of K Means is that it tries to minimize the <B> "Intra - Cluster" </B> distances and maximize the  <B> "Inter-cluster distances" </B>
  - This Algorithm can be used for <B CUSTOMER SEGMENTATION. </B>
 ## Let's try to make it simpler for you to understand the code
 Step 1) <B>  Initializing K with centroids </B> <br>
 Let us assume <B> K=3 </B> centroids. Here, <B> k </B> represents the number of clusters. 
 <B> Centroids </B> are data points which are centre of the clusters
 Usually we initialize the K with 5 as it provides a model with good accuracy.
 However, we need to keep this in mind that Increasing the value of K Decreases the error. <br>
 
 Step 2) <B> Distance Calculation </B> <br>
 This step is done to assign the data points to its nearest cluster.
 We can use the <B> Distance-Matrix </B> to find the nearest centroid to data points.<br>
 
 Step 3) <B> Assigning Data Points </B> <br>
 We assign the data points to the closest centroid. <br>
 
 Step 4) <B> Computing New Centroids for each Cluster </B> <br>
 Each cluster will be updated to be the mean for data points in its cluster.
 The Centroid of each of the clusters becomes the mean. <br>
 
 Step 5) <B> Repeat </B> the steps till there are no changes in the centroid. <br>
 
 ## Error
 Error in K Means is the total distance of each point from its centroid. <br>
