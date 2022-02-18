# Basic Perceptron
Perceptron using old school update.

Basic Perceptron. Used lecture notes from: https://www.cs.utah.edu/~zhe/pdf/lec-10-perceptron-upload.pdf

Can only classify things that are linearly separable, https://www.cs.cornell.edu/courses/cs4780/2018fa/lectures/lecturenote03.html

Notes:
- At this time backprop, and grad descent did not exist. Activation function was sign(Wx) or probably some step function.
- Using the Iris dataset, there is actually three classes here, because of the step function these old school perceptrons could only perform binary classification. So this implementation classifies 'Iris-setosa' from everything else.

-Implementation could be more elegant, but the conditional statements in the update function is there to show that updates only occur on misclassifications. 

Apparently these kinds of perceptrons lead to the AI winter?







