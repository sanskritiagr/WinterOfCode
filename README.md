# WinterOfCode(ML)
This project has 6 models - Linear Regression, Polynomial Regression, Logistic Regression, K- Nearest Neighbors, K- Means Clustering, Neural Networks. 
## Linear Regression
It is used to predict values of Y using fetures X. I made a function to train my model and get theta values. Then I used those theta to get Y for my testing data. Then I calculated Root Mean Squared Error.
#### Root Mean Squared Error = 1.829
## Polynomia Regression
It is used to predict values of Y using features and their nth degree. I started with n=2 and tried till n=4. I got maximum accuracy for n=3. Then, I made a function to train my model and get theta values. 
#### Root Mean Squared Error = 2.299
## Logistic Regression
It is used to model the probability of discrete outcomes and give the predicted Y values. We used sigmoid funtion. I used a function to train my data and get theta values. Then multiply those theta with test sample to get hypothesis. Then took sigmoid of it and the value with maximum probability was the predicted Y value. Then I compared it with given Y value to get accuracy.
#### Accuracy = 69.446%
