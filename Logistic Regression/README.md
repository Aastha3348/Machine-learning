# Logistic Regression
This File consists of the Source Code of Logistic Regression and explains the process of building the model.

## Here's what you need to know about Logistic Regression.
  - <B> Logistic Regression </B> is a <B> Statistical </B> and Machine Leraning </B> technique used to build models 
  for classifying records of a dataset based on the values of the input fields. 
  - Unlike <B> Linear Regression </B> where we predict <B> Continuous Variables </B> , <B> Logistic Regression </B> predicts <B> Binary Variables </B> such as <B> Yes/No </B>
  and <B> TRUE/FALSE </B>.
  - In <B> Regression Analysis </B> , logistic regression estimates the parameters of a logistic model which is a form of <B> Binary regression </B> .
## Applications
  - In Binary data like <B> 0/1 </B>, <B> Yes/No </B>, <B> TRUE/FALSE </B>.
  - For monitoring Customer buying details when you require <B> Probabilistic results </B> of a customer buying a particular product.
  - In linearly separable data.
  - To understand the imapct of a feature.
  ## Training Process 
    Step 1. Initialize Theta (θ) 
            * In logistic regression, θ is a vector of parameters of length m and we learn the values of those 
            parameters based off of n training examples. 
            * The number of parameters should be equal to the number of features of each data point. 
            
    Step 2. Calclate the Sigmoid function 
            A step function used in Logistic Regression.This function maps any real value into another value between 0 and 1.
            It is represesnted by 'σ' and calculated as 
                                        y cap = σ((θ^T)x).
                                        
    Step 3. Compare the output of y cap with actual output of customer, y, and record it as error. 
    
    Step 4. Calculate the error for all customers. 
    
    Step 5. Change the θ to reduce the cost.
    
    Step 6. Return to the Step 2. and repeat the steps untill the cost is reduced to minimum.
    
   ### Cost Function
   The cost function represents optimization objective. We create a cost function and minimize it by changing θ in order to obtain an accurate model with minimum error.
   
   ### Gradient Descent 
   It is an iterative approach to find the minimum of a function. We change the value of the parameter to minimize the cost. 
