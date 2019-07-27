---
title: "Neural Network"
date: 2019-07-27 12:31:47 -0400
categories:
  - Neural_Network
tags:
  - machine learning
  - deep learning
  - neural network
---

Neural network

## Contents  
1. [Before](#before)  
2. [Background](#background)  
  
### Before
LDA (linear discriminant analysis)  
(C, Kernel) SVM (support vector machine): quadratic optimization of hyper-plane with support vector; slack (allowable error; regularization parameter); kernel trick (high dimension mapping)  
Logistic regression  
A priori algorithm  
Decision tree/random&rotation forest: recursive partitioning (entropy), pruning  
AdaBoost (adaptive boosting; ensemble): weak learner/classfication (not random, weak probability composition)  
Bagging (bootstrap aggregating; ensemble):  distribution analogy(resample with replacement)  
Naive bayes: probability (prior and posterior) with some assumption  
Hidden markov models: likelihood, espectation-maximization (EM)  
Clustering: k-means, k-nearest neighbor, hiarchical, spectral (graph based), self-organizing map  
PCA (principal component analysis)/ t-SNE: linearity dimensionality reduction  
Neural net: perceptron, backpropagation; convolution, recurrent, recursive  
(Stacked, denoising, sparse, convolutional) autoencoder: non-linearity dimensionality reduction

### Background
False discovery rate  
Hyperparameter: learning rate, cost function, regularization parameter, mini-batch size, training repetition hidden layer units, weight initialization)  
Hyperparameter optimization: manueal search, grid search, random search, bayesian optimization  
Greedy layer-wise  
Activation function: step, sign, linear, sigmoid, tanh, ReLU (Rectifier Linear Unit); softmax  
Cost function: mean square error, cross-entropy cost function  
Whitening: distribution normalization (outside neural network)  
Batch normalization: distribution normalization (inside neural network by scale and shift)  
Regularization (L1, L2, max-norm)  
Dropout: node presentation probability (during training)  
DropConnect: weight presentation probailbility (during training)  
(Stochastic&probilistic weighting, max, mean) pooling: subsampling  
Maxout  
Data Augmentation
  
#### Reference
1. [Laon People][Laon People]  
2. [ratsgo's blog][ratsgos blog]  

[Laon People]: http://blog.naver.com/PostList.nhn?blogId=laonple&from=postList&categoryNo=22  
[ratsgos blog]: https://ratsgo.github.io/blog/categories/
