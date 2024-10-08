##### Link to CIFAR-10 example (regression) --> https://github.com/jglombitza/cifar_tutorial

![Example Event](images/footprint.png)

# Air shower reconstruction using deep neural networks
Train neural networks to reconstruct air-shower properties using detector responses measured at a hypothetic cosmic-ray observatory located at a high of 1400 m. The observatory features a cartesian array of 14 x 14 particle detectors with a distance of 750 m.

Each particle detector measures two quantities that are stored in the form of a cartesian image (2D array with 14 x 14 pixels).
We will use these images to train neural networks to reconstruct the energy of the events.

## Tutorial
We will use [jupyter](https://jupyter.org/) notebooks in the tutorial. As deep learning framework [Keras](https://keras.io/) is used.

For training the DNNs, we use Google colab to accelerate the training using a GPU. For opening the jupyter in colab, just click on the respective badge.

You can access the slides for the tutorial at:

Find more examples for deep learning in physics at www.deeplearningphysics.org/.

## Neural Network Playground
Open the neural network playground at: https://playground.tensorflow.org and train your first neural network

## Fully-connected network
Train a **fully-connected network** to reconstruct the energy of a cosmic-ray-induced air shower.  

<a target="_blank" rel="noopener noreferrer" href="https://colab.research.google.com/github/jglombitza/tutorial_nn_airshowers//blob/master/fully_connected.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="drawing" width="180"/> </a>

## Convolutional neural network
Train a **convolutional neural network** to reconstruct the energy of a cosmic-ray-induced air shower.  


<a target="_blank" rel="noopener noreferrer" href="https://colab.research.google.com/github/jglombitza/tutorial_nn_airshowers//blob/master/convolutional.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="drawing" width="180"/> </a>
