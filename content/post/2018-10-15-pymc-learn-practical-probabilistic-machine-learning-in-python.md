---
title: 'pymc-learn: Practical Probabilistic Machine Learning in Python'
author: Daniel Emaasit
date: '2018-10-15'
slug: pymc-learn-practical-probabilistic-machine-learning-in-python
categories:
  - Announcement
tags:
  - bayesian
  - pymc3
  - scikit-learn
  - machine-learning
---

PyMC3 is a Python package for probabilistic machine learning that enables users
to build bespoke models for their specific problems using a probabilistic
modeling framework. However, PyMC3 lacks the steps between creating a model and
reusing it with new data in production. The missing steps include: scoring a
model, saving a model for later use, and loading the model in production
systems. In contrast, *scikit-learn* which has become the standard
library for machine learning provides a simple API that makes it very easy for
users to train, score, save and load models in production. However,
*scikit-learn* may not have the model for a user's specific problem.
These limitations have led to the development of the open
source *pymc3-models* library which provides a template to build bespoke
PyMC3 models on top of the *scikit-learn* API and reuse them in
production. This enables users to easily and quickly train, score, save and
load their bespoke models just like in *scikit-learn*.

The ``pymc-learn`` project leverages the template in *pymc3-models* to
develop custom Bayesian models. This provides users with probabilistic models
in a simple workflow that mimics the scikit-learn API. 

#### References
1. Ghahramani, Z. (2015). Probabilistic machine learning and artificial intelligence. Nature, 521(7553), 452.

2. Bishop, C. M. (2013). Model-based machine learning. Phil. Trans. R. Soc. A, 371(1984), 20120222.

3. Murphy, K. P. (2012). Machine learning: a probabilistic perspective. MIT Press.

4. Barber, D. (2012). Bayesian reasoning and machine learning. Cambridge University Press.

5. Salvatier, J., Wiecki, T. V., &amp; Fonnesbeck, C. (2016). Probabilistic programming in Python using PyMC3. PeerJ Computer Science, 2, e55.

