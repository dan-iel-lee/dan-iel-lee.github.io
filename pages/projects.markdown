---
layout: page
title: Research+Projects
permalink: /research/
---

New webpage: <a href="https://dan-iel-lee.vercel.app/">dan-iel-lee.vercel.app</a>

## Publications


### [Online Minimax Multiobjective Optimization: Multicalibeating and Other Applications (NeurIPS 2022, *Selected for Oral Presentation*)](https://arxiv.org/abs/2108.03837)
Authors: **DL**, Georgy Noarov, Mallesh Pai, Aaron Roth

**Abstract:** 
We introduce a simple but general online learning framework in which a learner plays against an adversary in a vector-valued game that changes every round. Even though the learner's objective is not convex-concave (and so the minimax theorem does not apply), we give a simple algorithm that can compete with the setting in which the adversary must announce their action first, with optimally diminishing regret. We demonstrate the power of our framework by using it to (re)derive optimal bounds and efficient algorithms across a variety of domains, ranging from multicalibration to a large set of no regret algorithms, to a variant of Blackwell's approachability theorem for polytopes with fast convergence rates. As a new application, we show how to ``(multi)calibeat'' an arbitrary collection of forecasters -- achieving an exponentially improved dependence on the number of models we are competing against, compared to prior work.


### [An Existential Crisis Resolved: Type Inference for First-Class Existential Types (ICFP 2021, *Winner of Distinguished Paper Award*)](https://icfp21.sigplan.org/details/icfp-2021-papers/3/An-Existential-Crisis-Resolved-Type-Inference-for-First-Class-Existential-Types)
Authors: Richard A. Eisenberg, Guillaume Duboc, Stephanie Weirich, **DL**

**Abstract:** Despite the great success of inferring and programming with universal types, their dual—existential types—are much harder to work with. Existential types are useful in building abstract types, working with indexed types, and providing first-class support for refinement types. This paper, set in the context of Haskell, presents a bidirectional type-inference algorithm that infers where to introduce and eliminate existentials without any annotations in terms, along with an explicitly typed, type-safe core language usable as a compilation target. This approach is backward compatible. The key ingredient is to use *strong* existentials, which support (lazily) projecting out the encapsulated data, not weak existentials accessible only by pattern-matching.

### Single-Server Private Information Retrieval in the Shuffle Model. (Manuscript. In submission to Eurocrypt 2023)
Authors: Yuval Ishai, Mahimna Kelkar, **DL**, and Yiping Ma

## Theses

### Towards a Fundamental Theorem of Learning and Compression
Thesis for my Master's in Mathematics (2022), on finite sample compression schemes for concept classes of finite VC dimension.

<iframe src="https://drive.google.com/file/d/1i6R88UlDxGPE1SiiQ2q7VojhVN4XBa5Q/preview" width="640" height="480" allow="autoplay"></iframe>



## Talks, Surveys, Projects

### Talk: Expander Graphs (Fall 2021)
Slides for a 10 minute talk on expander graphs, for the [Directed Reading Program](https://www2.math.upenn.edu/~tbraz/drp/index.html).

<iframe src="https://drive.google.com/file/d/1iMmOVkWd2eAl1V6j_zoYIMRGq9X-i3e2/preview" width="640" height="480" allow="autoplay"></iframe>


### Talk: Hardness vs. Randomness (Spring 2021)
Slides and lecture notes for a talk I gave about *Hardness vs. Randomness* (Nisan, Wigderson 1994), for **CIS 700 Computational Complexity**.

<iframe src="https://drive.google.com/file/d/1Jbx9TO3n6tEJpAI_PqG-CPK8iq998gjz/preview" width="640" height="480" allow="autoplay"></iframe>

### Survey: Local Differential Privacy (Fall 2020)
Theory of differential privacy; especially in the local setting, and how it relates to classical learnability classes/results. Final project for **CIS 625 Theory of Machine Learning**.

<iframe src="https://drive.google.com/file/d/1Oc8WBw53xIjV2f_kuHmqf6wYpFHwrNud/preview" width="640" height="480" allow="autoplay"></iframe>



### Survey: A Game Theoretic Perspective on GANs and Training GANs (Spring 2021)
Generative Adversarial Networks, how they relate to game theory, and how the game theoretic perspective is being applied in research to improve generalization and trainability of GANs. Final project for **NETS 412 Algorithmic Game Theor**y.

<iframe src="https://drive.google.com/file/d/103xkrBgLfXWE37db7bB8buUeebBBydz3/preview" width="640" height="480" allow="autoplay"></iframe>

### Project: Understanding Self-Supervised Learning through BYOL: Bootstrap-your-own-latent (Fall 2021)
**Abstract:** In vision, self-supervised learning is an unsupervised method of learning rich feature representations from unlabeled images that can be used for improving performance on downstream tasks. In this work, we explore bootstrap-your-own-latent (BYOL), a recently developed self-supervised learning method that reduces computational expenses and produces state-of-the-art results. We implement a simplified version of the BYOL pipeline and perform experiments to study how various settings affect performance. The results suggest that (1) self-supervised pre-training is a form of regularization to address overfitting; (2) self-supervised learning relies on access to a very large unlabeled dataset; (3) the predictor is critical to BYOL's performance; (4) augmentations must be robust enough for the network to learn meaningful image features and some are much more useful for representation learning than others; and (5) the value of the target update parameter $\tau$ is critical to BYOL's success and adding a custom schedule for updating $\tau$ during training can boost performance.

<iframe src="https://drive.google.com/file/d/1OcPQl4p9_PqxD7XcyRwMAtweTukT18Ou/preview" width="640" height="480" allow="autoplay"></iframe>

### Project: [Haskell Type Checker and Evaluator with Quick Look based Impredicativity Support](https://github.com/dan-iel-lee/cis552-final-project) (Spring 2021)
An implementation of a parser, type checker, and evaluator. Support for user defined Algebraic Data Types, pattern matching, mutual recursion, higher rank polymorphism, impredicativity. Evaluator based on a small step operational semantics. Type checker is inspired by the Quick Look [paper](https://www.microsoft.com/en-us/research/publication/a-quick-look-at-impredicativity/). Final project for **CIS 552 Advanced Programming**.


### Project: [Category Theory Library for Cubical Agda](https://github.com/agda/cubical/tree/master/Cubical/Categories) (Winter 2020)
A library with definitions and fundamental results for one-categories in Cubical Agda, a constructive/computational implementation of Homotopy Type Theory. 
