---
title: "Natural Language Processing"
date: 2019-07-26 10:15:13 -0400
categories:
  - Natural_Language_Processing
tags:
  - machine learning
  - deep learning
  - natural language processing
---

Natural Language Processing

## Contents  
  1. [Analysis](#analysis)   
  2. [Algorithm](#algorithm)
  3. [Method](#method)   
  4. [Background_algorithm](#background_algorithm)
  
### Analysis
  Term-document (count word), word-context(count surrounded word), pair pattern  
  Similarity (relational, attributional): synonyms, meronyms, antonyms; hypernym  
  Phonology, morphology, syntax, semantics, reasoning  
  Pos-tagging (part of speech), parsing (dependency, constituency; named entitiy recognition), embedding (co-reference), basic dependencies, SRL (semantic role labeling)  
  Sentence splitting (corpus), tokenize, morphological analysis (text normalization; folding, stemming, lemmatization)  
  Emotional classification, machine transition, QA (question and answer), conversation
  
### Algorithm
  TF-IDF (term frequency-inverse document frequency), SVM (support vector machine), linear regression, naive bayesian, K-NN (k-nearest neighbor)  
  Network  
  Probability distribution: n-gram, LDA (Latent Dirichelet Allocation), pLSA (Probabilistic Latent Semantic Analysis)  
  CNN (convolutional neural network)  
  RNN (recurrent neural network, recursive neural network)  
  LSTM (long short term memory), GRU(gated recurrent unit), GAN(generative adversial network)  
  Encoder/Decoder: autoencoder, attention (similarity)
  
### Method 
  NNLM (neural network language model)  
  Word2Vec/GloVE/Fasttext: CBOW (continuous-bag-of-words), skip-gram/inner-product property/subword  
  Seq2Seq: attention  
  Embedding (sentiment specfic word, task specific): emotion, framework (S-Space, semantic vectors, gensim, pydsm, dissect)  
  Autoencoder (stacked denosing, combinatory categorial)
  
### Background_algorithm
  Similarity: common feature, ratio, simple matching, jacquard, overlap, cosine  
  Ratio (frequency, accuracy, ratio, probability, separation): odds(numerator), F1, F2, entropy  
  Morpheme extraction: Branching Entropy, Cohension Probability  
  MLE (maximum likelihood estimation)  
  Dimension reduction: SVD (singular value decomposition), PCA (principal component analysis), t-SNE (t-stochastic neghbor embedding)  
  Sampling (softmax loss update): candidate (part of data), negative (binary classification)  
  Smoothing (normalized topic)  
  Finite grammer
  
#### Reference
1. [ratsgo's blog][ratsgos blog]  

[ratsgos blog]: https://ratsgo.github.io/blog/categories/
