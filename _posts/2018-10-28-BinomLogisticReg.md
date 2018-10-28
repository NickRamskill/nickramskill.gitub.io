---
layout: post
title: Logistic Regression Mini-Project
subtitle: Binomial and Multiclass Logistic Regression Classification Algortihms
---

In Week 3 of the Andrew Ng Machine Learning programme, we were introduced to classification problems with a focus on logistic regression. The logistic regression algorithm is used to predict the probability of a categorical output variable based on the input variables to the model. 

After completing the lectures and assignments, firstly I implemented the binomial logistic regression algorithm to the Iris data set. In this dataset four physical characteristics of the flowers (sepal length, sepal width, petal length and petal width) were measured for three different varietals of the Iris flower (setosa, virginica and versicolor). The figure below shows the matrix of scatter plots for the Iris data set colored by the target variable (green: , red:, blue:). 



From this it can be seen that the setosa class is linearly seperable from the virginica and versicolor classes and can therefore be reformulated as a binary classification problem as is shown in the figure below.

As with the previous mini-project on linear regression, I decided to go the route of programming all of the steps (i.e. calculating the cost function and gradient descent) from scratch to ensure that I fully understood the translation from the theory to the practical application. Here is a [link](https://github.com/nickramskill/Machine-Learning-Projects){:target="_blank"} to the Jupyter notebook detailing the model development and testing. The data for the project was obtained from the UC Irvine Machine Learning Repository.  


