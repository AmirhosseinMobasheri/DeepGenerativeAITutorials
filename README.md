# ECE 1508: Deep Generative Models Tutorials #


As a TA of the course, I prepared and lectured 5 hands-on coding tutorials on various deep generative learning topics. The following is a summary of the contents of each tutorial file:

1. **Pytorch basics, Describing and training a neural network**
    - Introduction to Pytorch, Using Pytorch built-in datasets, loading and preparing data, describing a deep neural network in Pytorch, implementing a training loop for deep neural network.
    - Introduction to autoregressive language modeling, implementation of char-level tokenization, data preparation for autoregressive LM training, describing a simple LSTM in Pytorch and training it, text generation (inference) from a trained Language Model

2. **Transformer from Scratch, How to train an autoregressive model**
    - Coding all building blocks of a GPT-style language model from scratch including coding self-attention, positional embedding, mlp, embedding and de-embedding layers in a detailed, step-by-step manner and putting all them together to build a language model.
    - Training the described transformer-based language model using a cha-level tokenized toy dataset.
    - Implementing next-token prediction and text generation

3. **Energy-based Models, Boltzmann Machine, Gibbs and Langevin Sampling**
    - Building a fully visible Boltzamnn Machine and training it on a toy dataset using Gibbs sampling
    - Coding a Neural Energy-based Model, training it to learn a bi-modal distribution using Langevin sampling
  
    - 
4. **Generative Adversarial Models (GAN) and Wasserstein GAN (WGAN)**
    - Building a vanilla GAN consisting of discriminator and generator models
    - Training GAN on MNIST
    - Training a WGAN on MNIST
