# learning-compression
## overview
There are 2 seperate iPython notebooks in this repository corresponding to the 2 datasets : mnist.ipynb , svhn.ipynb
Initially we experiment with 30 epochs, but accuracy curve flattens much earlier at around 10 epochs. We train till 15 epochs
## neural network architecture
2 hidden layer, feed forward fully connected multi layered perceptron.
hlayer_1 : 1000 nodes
hlayer_2 : 1000 nodes

activation function : ReLU
optimizer function : Adam, SGD

## dataset download
mnist : http://yann.lecun.com/exdb/mnist/

svhn : http://ufldl.stanford.edu/housenumbers/   (format2 : cropped digits is used by us) ((.mat) files)

##Hyperparameters
Learning rate:
1. Adam : 0.0001 
2. SGD  : 0.001
