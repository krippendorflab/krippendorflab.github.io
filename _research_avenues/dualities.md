---
title: Dualities - a tool to tame dynamical systems and to surprise Mathematicians
layout: page
description:
---
Although dualities go back to the 1940s, especially the developments since the 1990s have transformed the calculational capabilities of physicists dramatically. This includes the dualities in quantum field theories (e.g. Seiberg dualities) and holographic dualities (AdS/CFT) which allows the calculation of correlation functions in a strongly coupled field theory via the calculation in a weakly coupled gravitational theory. In general one has multiple descriptions with different variables (fields/matter content) of the same dynamical system, i.e. these descriptions have the same partition function. The power of these multiple descriptions arises when one description is at strong coupling and the other is at weak coupling as this provides new ways to infer information about the system which are largely inaccessible (unless using expensive lattice simulations).

Dualities naturally connect with Machine Learning as follows: The dual weakly coupled descriptions are different and more "meaningful" representations of the same system which is at the heart of many representations obtained in deep learning. To give a flavour of the questions I am thinking about in this direction:

1. Do neural networks utilise these "meaningful" dual physics representations or how can we force them to find such representations?

2. How can we utilise deep architectures to find "new" dualities not yet known in physics?


### [Connecting Dualities and Machine Learning](https://arxiv.org/abs/2002.05169)
#### Philip Betzler, Sven Krippendorf

Dualities are widely used in quantum field theories and string theory to obtain correlation functions at high accuracy. Here we present examples where dual data representations are useful in supervised classification, linking machine learning and typical tasks in theoretical physics. We then discuss how such beneficial representations can be enforced in the latent dimension of neural networks. We find that additional contributions to the loss based on feature separation, feature matching with respect to desired representations, and a good performance on a ‘simple’ correlation function can lead to known and unknown dual representations. This is the first proof of concept that computers can find dualities. We discuss how our examples, based on discrete Fourier transformation and Ising models, connect to other dualities in theoretical physics, for instance Seiberg duality.
