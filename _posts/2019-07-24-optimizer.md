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
  5. [Adagrad](#adagrad)  
    Basic: SGD
  6. [RMSProp](#rmsprop)  
    Basic: Adagrad
  7. [AdaDelta](#adadelta)  
    Basic: Adagrad
  8. [Adam](#adam)  
    Basic: Momentum, RMSProp
  9. [Nadam](#nadam)  
    Basic: NAG + Adam
  10. [Other](#other)  
  
### GD

### SGD

### Momentum

### NAG

### Adagrad
    current stepsize = previous stepsize - alpha * gradient / [L2 norm][L2_norm]  
    problem: iteration ++ (larger) --> stepsize -- (too small) 
    solve: RMSProp, exponential moving average 
### RMSProp
    current stepsize = previous stepsize - eta * gradient / EMA  
    EMA = ratio of [L2 norm][L2_norm] and gradients^2 
### AdaDelta

### Adam

### Nadam

### Other
  1. Adadelta
  2. SparseAdam
  3. Adamax
  4. ASGD

[L2_norm]: https://sejik.github.io/
