# WinterOfCode(ML)
This project has 6 models - Linear Regression, Polynomial Regression, Logistic Regression, K- Nearest Neighbors, K- Means Clustering, Neural Networks.  
## Linear Regression
It is used to predict values of Y using fetures X. It is the first model I made. This is what I implemented.
I made a function to train my model and got theta values.
Then I used those theta values to get Y for my testing data.
Then I calculated Root Mean Squared Error by comparing it with the given testing Y values.
#### Root Mean Squared Error = 1.829
## Polynomia Regression
It is used to predict values of Y using features and their nth degree. 
I used my knowledge of linear regression to write its function.
I started with degree n=2 and tried till n=4. I got maximum accuracy for n=3. 
Then, I used function to train my model and get theta values. 
Those theta values were used to get test Y values.
Then subsequently Root Mean Squared Error was colculated.
#### Root Mean Squared Error = 2.299
## Logistic Regression
It is used to model the probability of discrete outcomes and give the predicted Y values.
First, we had to do one hot encoding on test and train Y values.
We used sigmoid funtion.
I made a function to train my data and get theta values.
Then multiply those theta with test sample to get hypothesisand then took sigmoid of it. 
Then I took the value with maximum probability to be the predicted Y.
Then I compared it with given Y test to get accuracy.
For accuracy, I subtracted given and predicted Y values and counted the no. of zeros. This gave me the number of correctly predicted values.
#### Accuracy = 69.446%
## K- Nearest Neighbors
It is used to predict the correct class for the test data.
My model first claculates distance of each testing data with training datas. 
Then it checks the k nearest points to predict class.
The predicted Y is compared with the given Y values to get accuracy. 
For accuracy, I used the same idea as I did in logistic regression.
#### Accuracy = 83.46%
## K- Means Clustering
This model groups the given data into clusters based on the similarity between them.
Firstly, I plotted a graph of wcss vs k. It came out to be minimum for k=30. 
So, I made 30 clusters for the dataset. 
First, we took random points to be center of our clusters.
Then, calculate the distance of each center with other points. 
The point having minimum distance with a center was assigned the cluster belonging to that center.
Then new centers were made by taking mean of points of that cluster.
Then this process is repeated till I get same value for centers.
Then I gave each cluster a label by using the given values for our data Y.
Though it is unsupervised learning and we are not supposed to calculate accuracy. Still I wanted to check my code. So, I printed accuracy.
#### Accuracy = 42.445%
## Neural Network
This model tries to predict outputs for the given inputs. It consist of 1 input layer, 1 hidden layer and 1 output layer.
I initialised thetas and biases, then use forward and back propagation to get optimum values. 
Those values of thetas and biases were used to get predicted Y values for testing data.
ERROR: I am getting only 1 output for ach example in train and test data.
I calculated accuracy. Though it has no meaning since I am getting only 1 output for each example.
##### Accuracy = 5.04%
