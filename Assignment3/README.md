# Assignment 1

## Problem Statement


1. The problems are adversarial attacks. During adversarial attacks, a small calculated perturbation in the input image largely affect the classifier output. Now, the purpose is to defend classifier against those attacks.

2. Succesfully train GANs and VAEs on three different datasets (CIFAR10, MNIST and FMNIST).

## Solution Overview

####Adversarial Defense:
    -------------------

I made the classifier robust against such adverserial attacks by imposing **Lipschitz constrain** and smoothening the labels(as we do in defense distillation).

####Note:
    ----

1. Files Fashion_mnist.ipynb and Cifar10.ipynb contain a classifier without defence and a classifier with defence on CIFAR and FMNIST datasets.

2. Files DCGAN.ipynb and Fully Connected GAN.ipynb contain GANs.

3. A VAE architecture on FMNIST can be found in VAE Fmnist.ipynb.

4. A detailed analysis of these techniques can be found in **Assignment3.pdf**.