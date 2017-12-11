# Nadam v. Adam
Comparison of Nadam and Adam optimization algorithms using example problems: (1) linear regression, (2) MNIST classification with logistic regression, and (3) MNIST classification with convolutional neural networks.

Each of the following files compare Adam and Nadam in a different setting:
1) linear_regression.ipynb
2) logistic_regression.ipynb
3) conv_nn.ipynb

Nadam and Adam are two state of the art optimization algorithms which are designed for convex objective functions but work well for non-convex objective functions like neural networks.

Adam utilizes the first and second moments of the gradients and comes up with an effective method for adaptive learning rate for different parameters. It works well in the online setting as well.
Nadam incorporates Nesterov momentum with the Adam algorithm.

More information on these algorithms can be found at:
<br />
"Adam: A Method for Stochastic Optimization"
https://arxiv.org/pdf/1412.6980.pdf
<br />
"Incorporating Nesterov Momentum into Adam" 
http://cs229.stanford.edu/proj2015/054_report.pdf
