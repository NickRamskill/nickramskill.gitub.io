---
layout: post
title: Logistic Regression Mini-Project (Part 1)
subtitle: Binomial Logistic Regression Classification
---

In Week 3 of the Andrew Ng Machine Learning programme, we were introduced to classification problems with a focus on logistic regression. The logistic regression algorithm is used to predict the probability of a categorical output variable based on the input variables to the model. 

## Binomial Logistic Regression

After completing the lectures and assignments, I implemented the binomial logistic regression algorithm to the Iris data set. In this dataset four physical characteristics of the flowers (sepal length, sepal width, petal length and petal width) were measured for three different varietals of the Iris flower (setosa, virginica and versicolor). The figure below shows the matrix of scatter plots for the Iris data set colored by the target variable (red: setosa, green: versicolor, blue: virginica). 

![Multiclass Iris Data Set]({{ "/img/Iris.png" | absolute_url }})

From this it can be seen that the setosa class is linearly seperable from the virginica and versicolor classes and can therefore be reformulated as a binary classification problem as is shown in the figure below (red: setosa, green: versicolor, virginica).

![Binomial Iris Data Set]({{ "/img/Iris-2.png" | absolute_url }})

As with the previous mini-project on linear regression, I decided to go the route of programming all of the steps (i.e. calculating the cost function and gradient descent) from scratch to ensure that I fully understood the translation from the theory to the practical application. 

Here is a [link](https://github.com/nickramskill/Machine-Learning-Projects){:target="_blank"} to the Jupyter notebook detailing the model development and testing. The data for the project was obtained from the UC Irvine Machine Learning Repository.  

As the setosa and the virginica/versicolor classes are linearly separable throughout the feature space, the logistic regression model obtained a 100 % prediction accuracy. Although this is a somewhat simple application of logistic regression, I found it to be extremely productive to programme the model from scratch as it helps me to translate the mathematical theory into code and solidify my understanding of how the different components fit together. 
