# Perceptron
PLA example for linear binary classification

PLA could only do linear and binary classification, which limits its usage.

This is simple practice for PLA algorithm.

PLA is like logistic regression that use MSE instead of cross entropy, is like neural network which only have single layer, thus is just a linear combination of input features, and ultimately pass through a sign function.

Due to the sign function as activation, it only have two kind of output, thus it could only do binary classification.

In PLA, we assume output class belong to 0 or 1, and update the weight by SGD in each training step.
