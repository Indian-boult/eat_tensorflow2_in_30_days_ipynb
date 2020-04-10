# Chapter 1: Modeling Procedure of TensorFlow


Although Tensorflow is designed in a smart way to be adaptive to various complex numerical computations, the most popular usage is implementation of machine learning models, especially for those of neural networks.

In principle, the neural network could be defined by graphs consist of tensors and trained through automatic differenciate.

However, for simplification, we recommend to use high-level Keras API in Tensorflow to implement the neural networks.

<!-- #region -->
The common procedures of implementing neural networks using TensorFlow are:

1. Data preparation

2. Model definition

3. Model training

4. Model evaluation

5. Model application

6. Model saving


**For the beginners, actually, data preparation is the most difficult part.** 

The most common data types are structured data, images, texts, and temporal sequences.

We are demonstrating the steps of modeling for these four data types through the following examples, respectively: (1) Predicting the survival on the Titanic; (2) Image classification on CIFAR2 set; (3) Classification of movie reviews on IMDB; (4) Predicting the terminate time of the COVID-19 pandemic in China.


<!-- #endregion -->
