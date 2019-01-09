# VanillaGAN-MNIST-Keras

Standard GAN implemented on top of keras/tensorflowGPU applied to the MNIST dataset.


## Vanilla GAN
Vanilla GANs are the simplest type of GAN and in this case the generator and the discriminator are just simple multi-layer perceptrons. Vanilla GANs simply just seek to optimize the mathematical equation using stochastic gradient descent.

This is the algorithm for the very first GAN. It was taken from the [paper](https://arxiv.org/abs/1406.2661) written by Goodfellow et al. in 2014:

<p align="center">
<img src="Vanilla_GAN_algo.png" alt="Vanilla GAN algorithm" width="400"/>
</p>

## Data
The dataset used for this project is the MNIST dataset composed of a 70,000 images of handwritten numbers.

<p align="center">
<img src="mnist.png" alt="MNIST dataset" width="400"/>
</p>

## Results
This is the progress on the Generator of my Vanilla GAN in only 100 epochs!


<p align="center">
<img src="GAN_progress.gif" alt="Porgress GAN" width="400"/>
</p>

