# Deep Learning with CIFAR-10 #

Deep learning is a subset of machine learning that is based on **artificial neural networks** (ANN). ANNs are comprised of input, hidden, and output layers that are connected via nodes that simulate nuerons in the human brain. The **CIFAR-10** dataset includes of 60,000 32x32 coloured images that can be categorized into 10 classes: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, and truck. This demonstration compares the performance of multi-layer perceptrons (MLP) and convolutional neural networks (CNN) in the task of image classification. The results indicate that the CNN has a higher accuracy than the MLP.

![CIFAR-10](https://production-media.paperswithcode.com/datasets/4fdf2b82-2bc3-4f97-ba51-400322b228b1.png)

## Multi-Layer Perceptron (MLP) ##

A multi-layer perceptron (MLP) is a fully-connected **feedforward neural network**. The connections between the layers are assigned weights. MLP uses **backprogpagation** as a supervised learning technique. During backpropagation, the weights are readjusted to minimize the difference between the actual and expected output. 

## Convolutional Neural Network (CNN) ##

A convolutional neural network (CNN) is a deep learning algorithm that is able to capture the spatial and temporal components of an image through the application of various filters. Three of the most important layers in a CNN are the **convolutional**, **rectified linear unit (ReLU)**, and **pooling** layers.
