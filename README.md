# Generative-Adversial-Networks
Built a generator and a discriminator model to make a Generative Adversial Networks for a fashion MNIST dataset. Used transpose convolutional layers for generator model and Convolutional Neural Network for discriminator model.

TRAINING METHADOLOGY-

I have created a generator and a discriminator model and combined these two models to make one Generator Adversarial Network Model.
I have used the normal distribution and generate the random points, and gave these points to the generator model to produce the fake data(images).
First, I have trained the discriminator model using the real data and the fake data. The error is backpropagated and the weights of the Discriminator Model are updated.
Now disabled the training for Discriminator Model and train the Generator Model by training the Generator Adversarial Network Model. The error is backpropagated and the
weights of the Generator Model are updated.

