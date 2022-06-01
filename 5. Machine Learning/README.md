[Instructions Doc](/5.%20Machine%20Learning/machine_learning_documentation.pdf)

* Perceptron
* Neural Network Tips
* Example: Linear Regression
* (Non-linear) Regression
* Digit Classification (Not Required)
* Language Identification (Not Required)

The main idea of implementation was to implement a binary perceptron in PerceptronModel class in models.py. The perceptron weights were already initialized to be 1 x dimensions parameter node. I completed the run method to compute the dot product of the stored weight vector and the given input. Then completed the get_prediction which returns 1 if dot product is non-negative else -1. Then the train method, which repeatedly loops over the data set and makes updates until the perceptron reaches convergence. 
