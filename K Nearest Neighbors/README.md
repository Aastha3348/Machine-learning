# K Nearest Neighbors
This file consists of the Source code for K Nearest Neighbors algorithm in Machine Leraning and the explanation about the concept.
## Here's what you need to know about K Nearest Neighbors
  - In KNN, We build a model to predict the class of a new or unknown case using the given dataset with predefined labels.
  - <B> K-Nearest Neighbors (KNN) </B> is one of the simplest algorithms used in Machine Learning for regression and classification problem. 
  - KNN algorithms use data available in the data set to classify new data points based on similarity measures like distance function. 
  Classification is done by a majority vote to its neighbors.
  - Suppose we take 5 nearest points from a data point <B> x </B>, then our <B> K </B> will b equal to 5 , i.e ,<B> K=5 </B>.
  ## Algorithm Steps 
    Step 1. Pick a value for K , where K is the number of neighbors.
    Step 2. Calculate the <B> Euclidean distance </B> of the unknown case 'x' from all the cases taken into consideration.
    
    Step 3. Select the K Nearest Neighbors in the training data that are "nearest" to unknown data points.
    
    Step 4. Count the number of data points from each category that are selected as K Nearest Neighbors.
    
    Step 5. Assign the unknown data point to the category for which the number of the neighbors is maximum.
  
### Eucledian Distance
<B> Euclidean distance </B> is the measure of the true straight line distance between two points in Euclidean space. <br>
The Eucledian distance between two data points from categories A and B with co-ordinates (x1,y1) and (x2,y2) respectively can be calculated as: <br>

                        sqrt[((x2-x1)^2)-((y2-y1)^2)] 
                        
### Note:
 A low value of <B> K </B> causes a highly complex model which might result in <B> Obver-Fitting </B>.
