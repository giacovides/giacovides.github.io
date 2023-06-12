---
layout: page
title: Variational Autoencoders and Generative Adversarial Networks
description: Coursework for 3rd Year module ELEC60009 - Deep Learning
img: assets/img/VAE_GAN.png
importance: 1
category: Machine Learning and Digital Hardware
---

In this coursework two main tasks were performed:   
  - The first task involved using the MNIST dataset to train the models and consequently generate new numbers:
    - A VAE was implemented with and without KL divergence loss and trained on the MNIST dataset by adjusting
    hyperparameters such as the batch size, the optimiser and the number of epochs.
    - A GAN model was implemented and trained on the MNIST dataset by adjusting hyperparameters such
    as the dimensionality of the initial random sample and the number of epochs.
    - The optimal Inception Score and MSE  of the two models were compared and linked to the qualitative
    results obtained.

 - The second task involved colouring B&W images using different models:
   - A cGAN model was firstly trained and developed to colour the images by predicting the RGB pixel-wise
   values of the B&W images
   - A UNet autoencoder trained with a MAE loss was then implemented to predict directly the RGB image
   without any GAN based learning strategy.
   - The quantitative results (MAE, MSE) and qualitative results of the two models were compared to
   understand the differences between them


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/VAE_GAN.png" title="vae and gan image" class="center rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    An illustration of a VAE and a GAN depicting the differences between the two models.
</div>
