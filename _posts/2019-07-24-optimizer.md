---
title: "Optimizer"
date: 2019-07-24 12:53:28 -0400
categories:
  - Optimizer
tags:
  - machine learning
  - deep learning
  - optimizer
---

Optimizer

## Contents  
  1. [GD](#gd): gradient descent  
  2. [SGD](#sgd): stochastic gradient descent  
    Basic: GD
  3. [Momentum](#momentum)  
    Basic: SGD
  4. [NAG](#nag): nesterov accelragted gradient    
    Basic: Momentum
  5. [Adagrad](#adagrad): Adaptive Gradient  
    Basic: SGD
  6. [RMSProp](#rmsprop)  
    Basic: Adagrad, Momentum
  7. [AdaDelta](#adadelta): adaptive delta  
    Basic: Adagrad
  8. [Adam](#adam): adaptive moment estimation  
    Basic: RMSProp + Momentum
  9. [Nadam](#nadam): nesterov accelerated adaptive moment estimation  
    Basic: NAG + Adam
  10. [Other](#other)  
  
### GD
  step: weight * gradients (whole dataset)  
  problem: huge memory  
  solution: SGD, using partial data & more steps
### SGD
  step: weight * gradients (mini-batch)  
  problem: very slow  
  solution1: Momentum, exponential weight average of gradient  
  solution2: Adagrad, L2 norm of gradient
### Momentum
  step: exponential weight average of gradient (gradient calculation: origin)  
  problem1: over caculated momentum  
  solution1: NAG, change gradient calculation points to momentum point  
  problem2: variety of weight feature  
  solution2: RMSProp & Adam, exponential weight of Adagrad & momentum gradient
### NAG
  step: exponential weight average of gradient (gradient calculation: momentum point)  
  problem: variety of weight feature  
  solution: Nadam, 
### Adagrad
  step: weight * gradients (L2 norm)  
  problem1: stepsize shrinking to learn nothing  
  solution1: RMSProp, exponential moving average
### RMSProp
  step: exponential weight average of gradient (L2 norm)  
  problem: first order optimization  
  solution: AdaDelta, second order optimization (inverse unit)
### AdaDelta
  step: exponential weight (with exponential step weight) average of gradient  
  problem: variety of weight feature  
  solution: Adam, momentum gradient
### Adam
  step: exponential weight (with exponential step weight) average of momentum gradient  
  problem: over caculated momentum  
  solution: Nadam, change gradient calculation points to momentum point
### Nadam
  step: exponential weight (with exponential step weight) average of NAG gradient  

### Other
  1. SparseAdam
  2. Adamax
  3. ASGD
  4. AMSGrad: Adam with max value instead exponential average value
  
#### 참조 사이트
1. BEOMSU kIM'S blog: http://shuuki4.github.io/deep%20learning/2016/05/20/Gradient-Descent-Algorithm-Overview.html  
2. Sebastian Ruder's blog: http://ruder.io/optimizing-gradient-descent/  
3. Konvergen.AI: https://medium.com/konvergen/modifying-adam-to-use-nesterov-accelerated-gradients-nesterov-accelerated-adaptive-moment-67154177e1fd  
