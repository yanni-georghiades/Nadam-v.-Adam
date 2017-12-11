# Nadam v. Adam
Authors: Ashish Katiyar, Dave Van Veen, Yanni Georghiades

Comparison of Nadam and Adam optimization algorithms using example problems: (1) linear regression, (2) MNIST classification with logistic regression, and (3) MNIST classification with convolutional neural networks.

Please view each of the following notebooks, which compare Adam and Nadam in these three different settings:
1) linear_regression.ipynb
2) logistic_regression.ipynb -- takes ~1 hr to run first must unzip data/MNIST_data.zip
3) conv_nn.ipynb -- takes ~1 hr to train networks and requires standard PyTorch installation

Nadam and Adam are two state of the art optimization algorithms which are designed for convex objective functions but work well for non-convex objective functions like neural networks.

Adaptive Moment Estimation (Adam) utilizes an exponentially decaying average of both past gradients and past squared gradients to estimate first and second moments of the gradients. This allows Adam to effectively compute adaptive learning rates for each parameter. It works well in the online setting as well.
Nesterov-accelerated Adaptive Moment Estimation (Nadam) incorporates Nesterov momentum, which is at times superior to vanilla momentum, into the Adam algorithm.

More information on these algorithms can be found at:
<br />
"Adam: A Method for Stochastic Optimization"
https://arxiv.org/pdf/1412.6980.pdf
<br />
"Incorporating Nesterov Momentum into Adam" 
http://cs229.stanford.edu/proj2015/054_report.pdf
<br />
"An Overview of Gradient Descent Optimization Algorithms"
https://arxiv.org/pdf/1609.04747.pdf
