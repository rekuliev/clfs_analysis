# Analysis of classification algorithms using the example of moons dataset
Task:

In this test task you are supposed to use a toy dataset to compare different classifiers. First, create a dataset in the following way: 

X, y = make_moons(n_samples=1000, noise=.5, random_state=0) 

* Standardize the features and split it into training and testing dataset. 
* Try following classification methods: 
  * Linear SVM; 
  * RBF (kernel) SVM; 
  * Decision tree; 
  * Random forest; 
  * Any boosting algorithm; 
  * KNN

Obtain training and testing error and explain your observations 
* Plot the decision boundaries of each classifier (create a meshgrid of x and 
y, make predictions on grid points and do contour plot. 
* Decide on the best model and give your reasoning about it.
