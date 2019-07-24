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
  1. Adadelta
  2. Adagrad
    current stepsize = previous stepsize - alpha * gradient / [L2 norm][L2_norm]
    problem: iteration ++ (larger) --> stepsize -- (too small)
    solve: RMSProp, exponential moving average
  3. RMSProp
    current stepsize = previous stepsize - eta * gradient / EMA
    EMA = ratio of [L2 norm][L2_norm] and gradients^2
  3. Adam
  4. SparseAdam
  5. Adamax
  6. ASGD
  7. RMSProp
  8. SGD

[L2_norm]: https://sejik.github.io/
