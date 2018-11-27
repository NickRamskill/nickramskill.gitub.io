---
layout: post
title: Neural Networks
subtitle: Developing a Neural Network for Handwritten Digit Recognition
---

In Week 5 of the Andrew Ng Machine Learning course we were introduced to neural networks. This has been an area that I have been looking forward to learning about for quite a while now and Andrew Ng's course certainly did not disappoint. In this week's mini-project I have implemented a neural network classification algorithm from scratch in Python and applied to the handwritten digit recognition problem introduced in the previous posting.

Here is a [link](https://github.com/nickramskill/Machine-Learning-Projects){:target="_blank"} to the Jupyter notebook detailing the model development and testing. 

In this mini-project I have used gradient descent to optimize the parameters in training the model. Whenever I am developing or testing a new model, I like to record the value of the loss function after each iteration to check that the model is converging. 

![Gradient Descent]({{ "/img/NN-J-Iter.png" | absolute_url }})

With this model, I achieved a prediction accuracy of 94 % (compared to 88 % accuracy with my home-built logistic regression algorithm). 

The application of neural networks in machine vision is a subject that I am extremely interested in and I look forward to developing my models further and apply them to so exciting challenges in this area.
