# Convolutional-Neural-Networks
Speech Denoising using 1D and 2D CNNs

Notebook Speech_Denoising_CNN.ipynb contains code which is used to train a Convolutional Neural Network using tensorflow to remove noise
from an audio signal. We train the neural network by giving speech with noise and clean speech as input and output. We then test by 
giving a new signal with noise and generate clean output. We use Signal-to-noise ratio to measure the performance of the neural network.

We train two neural networks - 1D convolution neural network, 2D convolutional neural network. The output obtained for the two test audio
signals from the two networks are in the data folder.
