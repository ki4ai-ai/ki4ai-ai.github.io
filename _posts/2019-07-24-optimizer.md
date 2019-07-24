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
  3. Momentum 
    Basic: SGD
  4. NAG: nesterov accelragted gradient
    Basic: Momentum
  5. Adagrad  
    Basic: SGD
  6. RMSProp  
    Basic: Adagrad
  7. AdaDelta  
    Basic: Adagrad
  8. Adam  
    Basic: Momentum, RMSProp
  9. Nadam  
    Basic: NAG + Adam
    
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

[L2_norm]: https://sejik.github.io/
