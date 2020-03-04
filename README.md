# Variational AutoEncoder


### Description: 

Generative Modeling is a subset of AI. This class of methods are different from the usual methods used: Classification and Regression. There are multiple use-cases of Generative Modeling: Denoising, Compression, Image Generation and many more.
Here, I have implemented a Variational AutoEncoder in TensorFlow on Fashion MNIST DataSet.
The key difference between a Vanila AutoEncoder and VAE is that in sampling of Latent Encoding Space. 
VAE is a Bayesian Approach where we encode a Mean and a Standard Deviation for an attribute in the Encoding Layer.
Further we sample from this latent space and try to regenerate new images using a Decoder Network.

### Dataset: 

Fashion-MNIST is a dataset of Zalando's article images—consisting of a training set of 60,000 examples and a test set of 10,000 examples. Each example is a 28x28 grayscale image, associated with a label from 10 classes. Zalando intends Fashion-MNIST to serve as a direct drop-in replacement for the original MNIST dataset for benchmarking machine learning algorithms. It shares the same image size and structure of training and testing splits.


### Architecture:


Working of VAE:

![VAE Architecture](https://github.com/kushalvala/variational-autoencoder/blob/master/artifacts/VAE-Architecture.png)
