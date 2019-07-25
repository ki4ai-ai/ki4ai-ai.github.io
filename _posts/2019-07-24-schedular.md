---
title: "Schedular"
date: 2019-07-24 17:01:22 -0400
categories:
  - Schedular
tags:
  - machine learning
  - deep learning
  - schedular
---

Schedular: Step, MultiSteip, CosineAnnealing, ReduceLROnPlateua, WarmUpLR

## Contents  
  1. [Step](#step)  
  2. [MultiStep](#multistep)  
  3. [CosineAnnealing](#cosineannealing)  
  4. [ReduceLROnPlateua](#reducelronplateua)  
  5. [WarmUpLR](#warmuplr)  
  
### Step
  Learning rate variation: Step

### MultiStep
  Learning rate variation: MultiStep

### [CosineAnnealing][cosineannealing]  
  Learning rate variation: Cosine Function
  
### [ReduceLROnPlateua][reducelronplateua]  
  Learning rate variation: Stop impoving point
  
### [WarmUpLR][warmuplr]
  Learning rate varaiation: gradually increasing
  
#### Reference
1. [CosineAnnealing][cosineannealing]  
2. [ReduceLROnPlateua][reducelronplateua]  
3. [Pytorch warmuplr][warmuplr]

[cosineannealing]: https://arxiv.org/abs/1608.03983
[reducelronplateua]: https://pytorch.org/docs/stable/_modules/torch/optim/lr_scheduler.html
[warmuplr]: https://github.com/ildoonet/pytorch-gradual-warmup-lr
