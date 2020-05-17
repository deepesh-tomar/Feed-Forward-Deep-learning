# Feed-Forward-Deep-learning

This file contains code for feed forward algorithm from scratch,
dataset used is make-blobs from sklearn

OUTPUT:-
For 2 input variables and binary output
1)	1st hidden layer has 3 neurons and 2nd hidden layer has 5 neurons
	2000 epochs and 0.001 learning rate
	accuracy on training set is 98%
	accuracy on validation set is 95% 

2)	1st hidden layer has 2 neurons and 2nd hidden layer has 3 neurons
	2000 epochs and 0.001 learning rate
	accuracy on training set is 98%
	accuracy on validation set is 94%

3)	1st hidden layer has 10 neurons and 12nd hidden layer has 5 neurons
	2000 epochs and 0.01 learning rate
	accuracy on training set is 98%
	accuracy on validation set is 94%

4)	1st hidden layer has 10 neurons, 2nd hidden layer has 12 neurons, 3rd layer has 5 neurons and 4th layer has 7 neurons
	2000 epochs and 0.01 learning rate
	accuracy on training set is 98%
	accuracy on validation set is 94% 
  
5)	total layers 7; neurons [10, 12, 5, 7, 5, 8, 2]
	5000 epochs and 0.001 learning rate
	accuracy on training set is 71%
	accuracy on validation set is 69% 

  
This trend shows that it's not neccessary that increasing more neurons or layers will improve output predictions, on the contrary adding too make parameters and neurons can lead to overfitting which happens when machine goes through data too many times and memorise the training data and increase prediction percent drastically but when new test data is presented as it has learned training data and has not learned to generalize for new test data
