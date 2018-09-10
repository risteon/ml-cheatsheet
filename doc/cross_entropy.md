---
title: "Basics PDF"
author: [Christoph Rist]
date: "2018-09-09"
subject: "Cross-Entropy"
keywords: [Probability, Loss]
...

# Chapter 1

## Cross Entropy Loss

$p$: true distribution

$q$: output distribution

$$
    H(p, q)  = \mathbb{E}_p\left[-\log q\right] = H(p) + D_{KL}(p||q) \\
\text{Discrete $p$ and $q$:}  \\
    H(p, q)  = - \sum_{x} p(x) \log q(x) \\
\text{Continuous $p$ and $q$:} \\
    H(p, q)  = - \int_X P(x) \log Q(x) dr(x)\\
$$

## Generative Adversarial Networks

Two-player minimax game with value function $V(D, G)$:

$$
\min_{G} \max_{D} V(D,G) = \mathbb{E}_{\mathbf{x}\sim p_{data}(x)} 
$$

## Markdown

| a | f | s |   |   |
|---|---|---|---|---|
|   |   | 3 |   |   |
|   |   |   | 2 |   |
|   |   |   |   | 1 |
