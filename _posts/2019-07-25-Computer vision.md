---
title: "Computer Vision"
date: 2019-07-25 16:21:53 -0400
categories:
  - Computer_vision
tags:
  - machine learning
  - deep learning
  - computer vision
---

Computer Vision

## Contents  
  1. [CNN](#cnn): convolution neural network  
  2. [LeNet](#lenet)  
  3. [ZFNet](#zfnet)  
  4. [GoogleNet](#googlenet)  
  5. [VGGNet](#vggnet)  
  6. [ResNet](#resnet)  
  
### CNN
  Neural network with convolution (ex. 3*3 filter(kernel))  
  Advantage of convolution: locality (shared weight, max(average) pooling); stride, padding
### LeNet 
  2 dimension input, average pooling  
  3 convolution layer (5*5 filter), 1 full connected layer
### AlexNet
  3 dimension input, ReLU, max pooling, response normlization, dropout, data augmentation  
  5 convolution layer (11*11*3, 5*5*48, 3*3*256 filter), 3 full connected layer (result: softmax)
### ZFNet
  Parameter optimization by feature visualization (deconvolution)  
  Visualization optimization: feature extraction(edge, corner color, junction, object)
  Deconvolution: localization
### GoogleNet
  Deeper network by 9 * inception module with 1*1*n filter (and various n*n convolution and pooling)  
  Auxiliary classifier: sub-output for backpropagation(vanishing gradient avoidance)
  cf. NIN: convolution with multi layer perceptron instead of pooling (result: pooling)
### VGGNet

### ResNet
  
#### Reference
1. [Laon People][Laon People]  

[Laon People]: http://blog.naver.com/PostList.nhn?blogId=laonple&from=postList&categoryNo=22
