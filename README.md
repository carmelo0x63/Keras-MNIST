# Keras-MNIST
Jupyter notebook to train a model in Keras against the MNIST database

[Keras](https://keras.io/) is an open-source library, authored by François Chollet, that provides a Python interface for artificial neural networks.<br/>
The [MNIST database](https://en.wikipedia.org/wiki/MNIST_database) (Modified National Institute of Standards and Technology database) is a large database of handwritten digits that is commonly used for training various image processing systems.<br/>

----

### Requirements and quick setup
```
$ git clone https://github.com/carmelo0x63/Keras-MNIST.git && cd Keras_MNIST

$ source bin/activate

(Keras_MNIST) $ python3 -m pip install --upgrade jax jupyter keras matplotlib numpy

(Keras_MNIST) $ jupyter lab --no-browser --ip 0.0.0.0 --port 8888
```
Follow the instructions on how to connect to Jupyter by using a browser.<br/>

### Files
- `Matplotlib_test.ipynb`: quick example combining Keras, MNIST, and Matplotlib to display the contents of the datatset
- `Keras_MNIST.ipynb`: step-by-step guide on how to create a neural network in Keras, train it, then use it for inference

