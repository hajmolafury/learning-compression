# learning-compression
## overview
There are 2 separate iPython notebooks in this repository corresponding to the 2 datasets : mnist & svhn

MLP trained for 20 epochs

Graph plotting : plotly library (interactive graphs)

TO SEE GRAPHS PLEASE VIEW IN COLAB (link present on top of mnist_update.ipynb)

## neural network architecture
2 hidden layers, feed forward, fully-connected, multi layered perceptron.
- hlayer_1 : 1000 nodes
- hlayer_2 : 1000 nodes

* activation function : ReLU
* optimizer function : Adam, RMSProp, SGD

## dataset download
mnist : http://yann.lecun.com/exdb/mnist/
In our code, we import the mnist dataset from tensorflow.examples.tutorials.mnist

svhn : http://ufldl.stanford.edu/housenumbers/   (We have used : format2, cropped digits)

