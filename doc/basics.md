---
title: "Basics PDF"
author: [Christoph Rist]
date: "2018-09-09"
subject: "Cross-Entropy"
keywords: [Probability, Loss]
...

# Cross Entropy Loss

$p$: true distribution

$q$: output distribution

$$
\label{eq:neighbor-probability}
    H(p, q)  = \mathbb{E}_p\left[-\log q\right] = H(p) + D_{KL}(p||q) \\
\text{Discrete $p$ and $q$:}  \\
    H(p, q)  = - \sum_{x} p(x) \log q(x) \\
\text{Continuous $p$ and $q$:} \\
    H(p, q)  = - \int_X P(x) \log Q(x) dr(x)\\
$$

# Generative Adversarial Networks

...Some text
