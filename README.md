# Coursera's Machine Learning Course offered by Stanford University

### Assignment 1, (Linear Regression):
Implementation of the cost and gradient for linear regression with one variable to predict profits for a food truck.
If a CEO of a restaurant franchise and considering different cities for opening a new outlet. The chain already has trucks in various cities and we've data for profits and populations from the cities. So we will use this data to select which city to expand to next.

#### Training data with linear regression fit:
![image](https://user-images.githubusercontent.com/25883512/56217076-e06fde00-6062-11e9-8141-bb3ed8bfa9c5.png)

#### The surface and contour plots of J(theta) using the surf and contour commands.
![image](https://user-images.githubusercontent.com/25883512/56217156-06957e00-6063-11e9-9aad-990e5c99cb37.png)

### Linear regression with multiple variables:

Predict the prices of houses. Suppose you are selling your house and you want to know what a good market price would be. 
The training set consist of: first column is the size of the house (in square feet), the
second column is the number of bedrooms, and the third column is the price of the house.

#### Convergence of gradient descent with an appropriate learning rate:
plots the J values against the number of the iterations if the learning rate is in a good range, the cost will decrease with the number of iterations.

![image](https://user-images.githubusercontent.com/25883512/56217684-f03bf200-6063-11e9-9a9b-3dddea1c0e64.png)



### Assignment 2, (Logistic Regression):
Implementation of the cost and gradient for logistic regression using a built-in function (fminunc) to find the optimal parameters theta and plot the decision boundary.
If the administrator of a university department want to determine each applicant's chance of admission based on their
results on two exams. with historical data from previous applicants Use this data to build a classification model that estimates an applicant'sprobability of admission.
 
#### First, Logistic Regression with data points that are linearly separable: 

![image](https://user-images.githubusercontent.com/25883512/56214188-b667ed00-605d-11e9-9783-8151c2704eba.png)

![image](https://user-images.githubusercontent.com/25883512/56214140-9c2e0f00-605d-11e9-8ad0-938e2c0a747f.png)

#### Second, Logistic Regression with data points that are not linearly separable, by adding polynomial features to the data matrix:

![image](https://user-images.githubusercontent.com/25883512/56213276-fd54e300-605b-11e9-8eea-b2aa299725ae.png)

#### By Tuning the values of lambda to see how regularization affects the decision boundary:
lambda = 1
![image](https://user-images.githubusercontent.com/25883512/56213371-2d9c8180-605c-11e9-8a0b-e01e035ef0e7.png)

lambda = 10
![image](https://user-images.githubusercontent.com/25883512/56213791-fe3a4480-605c-11e9-85f9-fdaccd421704.png)

lambda = 100
![image](https://user-images.githubusercontent.com/25883512/56213870-22962100-605d-11e9-9738-da95d589ea43.png)

### Assignment 3, (Multi-class Classification and Neural Networks):
Implementation of one-vs-all logistic regression and neural networks to recognize hand-written digits (from 0 to 9).
![image](https://user-images.githubusercontent.com/25883512/56221454-8e32bb00-606a-11e9-94df-6842bdd002a9.png)

