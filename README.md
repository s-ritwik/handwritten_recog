# handwritten_recog
in python shell 
>>> import mnist_loader
>>> training_data, validation_data, test_data = \
... mnist_loader.load_data_wrapper()
"""data loaded,we will set up network with 30 hidden neurons"""
>>> import network
>>> net = network.Network([784, 30, 10])
use stoch gradient to learn form train_data over 30 epochs,or 16,with alpha learnng rate as 3,and mini batch size of around 10
>>> will take a few minutes to run
>>> might give upto 96% accuracy at its peak ,use 100 layers for upto 97percent,
