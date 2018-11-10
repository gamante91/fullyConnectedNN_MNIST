# fullyConnectedNN_MNIST

This is the "Hello World" equivalent of Machine Learning: 

a two fully connected layers neural network trained on the MNIST (http://yann.lecun.com/exdb/mnist/) dataset to classify digits.

The Neural Network is coded in PyTorch and has an input layer of size 784, as the inputs are 28x28 grayscale images, an hidden layer of size 500 and an ouput layer of size 10 (digits from 0 to 9).

Choiche of hyper parameters:
- Learning Rate (alpha): 0.001
- Loss function: Cross Entropy Loss
- Optimizer: Stochastic Gradient Descent

After being trainer, the Neural Network reached an accuracy on the 10000 test images of 86.71%
