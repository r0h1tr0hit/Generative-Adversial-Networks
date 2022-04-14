# Generative-Adversial-Networks
#### Built a generator and a discriminator model to make a Generative Adversial Networks for a fashion MNIST dataset. Used transpose convolutional layers for generator model and Convolutional Neural Network for discriminator model.

![GAN Model](GAN_model.png)

### TRAINING METHADOLOGY-

* Created a generator and a discriminator model and combined these two models to make one Generator Adversarial Network Model.
* Used the normal distribution to generate the random data points, and provide these data points to the generator model to produce the fake data(images).
* Firstly, Trained the discriminator model using the real data and the fake data together. The error is backpropagated and the weights of the Discriminator Model are updated.
* Now disabled the training for Discriminator Model and train the Generator Model by training the Generator Adversarial Network Model. The error is backpropagated and the weights of the Generator Model are updated.
