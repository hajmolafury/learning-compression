# learning-compression
## overview
There are 2 separate iPython notebooks in this repository corresponding to the 2 datasets : mnist & svhn
Initially, we trained the MLP for 30 epochs, but we observe that the accuracy curve flattens much earlier (5-7 epochs). 
We train for 15 epochs.
## neural network architecture
2 hidden layers, feed forward, fully-connected, multi layered perceptron.
hlayer_1 : 1000 nodes
hlayer_2 : 1000 nodes

activation function : ReLU
optimizer function : Adam, SGD

## dataset download
mnist : http://yann.lecun.com/exdb/mnist/

svhn : http://ufldl.stanford.edu/housenumbers/   (format2 : cropped digits is used by us) ((.mat) files)

## Hyperparameters
Learning rate:
1. Adam : 0.0001 
2. SGD  : 0.001
