# Complex_Convolutional_Neural_Network_Architecture

This repository conatins my implemetations of some of the famous, complex Convolutional Neural Net Archiectures. The models have been developed from scratch using Tensorflow's 
Keras functional API, which is a way to create models that are more flexible than the tf.keras.Sequential API. The functional API can handle models with non-linear topology, 
models with shared layers, and models with multiple inputs or outputs. This architecture makes it possible for the neural network to learn both deep patterns (using the deep path)
and simple rules (through the short path).

## List and short description of developed models

  * Alexnet - 
  * Xception - 
  * GoogleNet - 
  * Resnet - 
  * Unet - 
  * MobilNet - 
 
 ![Legend](https://github.com/Jash-2000/Complex_Convolutional_Neural_Network_Architecture/blob/main/Images/download.png)
 
## Keras Functions used and their explaination

 * Input() - This is just the defination of an input layer and has nothing to do with the functioning or structure of the model.
 * Conv2D() - Implements a 2D convolution on the previous layer. It creates <no of filters> numer of outputs and then concatenates them into 1 layer i.e.along the z-axis.
 * MaxPool2D() - Implements pooling of the previous layer by transmitting only the largest neuron from a pool of neurons.
 * AvgPool2D() - Implements pooling of the previous layer by transmitting the average value of all the neuron from a defined pool.
 * BatchNormalization() - Normalizes the neurons by shrinking down the values in the range of 0 to 1.
 * Flatten() - Flattens a layer i.e makes in 1D
 * Dense() - A fully connected dense multi-layer perceptron.
 * Dropout() - The Dropout layer randomly sets input units to 0 with a frequency of rate at each step during training time, which helps prevent overfitting.
 * Model() - Defines a keras model.
 * plot_model() - Plots the structure of the model
 * Concatenate()
 
## Transfer Learning

Transfer learning (TL) is a research problem in ML that focuses on storing knowledge gained while solving one problem and applying it to a different but related problem. For example,
knowledge gained while learning to recognize Cats could apply when trying to recognize Tigers. In this repo, I have also trained the developed models on various objects and have 
saved the weights as tensorflow weights. Feel free to download thoses weights, add your own layers and implement Transfer Learning for your project. 
