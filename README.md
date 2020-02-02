# SupportVectorMachine
This project implements SVM from very scratch for multiclass classification problem

# About Dataset
It is a UCI dataset for Nursery admissions in public schools. The database contains 12960 instances with 8 attributes and 5 labels for classification.

# Algorithm used

SVM works on the simple logic of finding a decision boundary between binary classes and maximize the margin i.e. the distance between decision boundary and the closest data points. These points are also known as support vectors so SVM doesn’t get affected by the outliers. 
As we have a multiclass and categorical dataset. We converted it into discrete numerical data using One Hot Encoding technique. But this process increased the dimensions of the dataset from 8 dimensions to 27 dimensions. So we decided to go with the dual formulation of the SVM.

For the training model in the dual formulation of SVM we have used the SMO algorithm. The SMO algorithm gives an efficient way of solving the dual problem of the (regularized) support vector machine optimization problem.

# Results:
Final Accuracy: 63.19845857418112
