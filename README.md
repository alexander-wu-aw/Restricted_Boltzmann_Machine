# Restricted_Boltzmann_Machine
A manually built restricted boltzmann machine used as a recommender system. It looks at a customer movie preferences and decides wether or not they will like a new movie.

A dataset is obtained that comprises of many users and their respective ratings for multiple movies. A test and training set is made by selecting random movie ratings for each user and ommiting the rest.

The creation of the class of RBM includes functions that initialize the model, predict the probability of the hidden node given the visible node, predict the probability of the visible node given the hidden node, and that trains the model.

The model is then trained on the training set. Then, it tries to predict the movies we have chosen to ommit in the training set and compares this to the real values in the test set.

This model was built with the help of the Deep Learning Udemy Course.
