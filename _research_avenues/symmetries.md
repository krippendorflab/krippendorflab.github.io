---
title: Symmetries in Physics and ML
layout: page
description: 
---

Symmetries are at the heart of our best models in fundamental physics, aka the Standard Model of Particle Physics and Cosmology.
Symmetries are at the heart of the best models in machine learning such as Convolutional Neural Networks.

With this anaphora I want to stress that mathematical structures have proven to be useful in two separate domains. By combining insights from both fields, we develop new techniques to improve simulations and to find new mathematical structures.


### [Detecting Symmetries with Neural Networks](https://arxiv.org/abs/2003.13679)
#### Sven Krippendorf, Marc Syvaeri

Identifying symmetries in data sets is generally difficult, but knowledge about them is crucial for efficient data handling. Here we present a method how neural networks can be used to identify symmetries. We make extensive use of the structure in the embedding layer of the neural network which allows us to identify whether a symmetry is present and to identify orbits of the symmetry in the input. To determine which continuous or discrete symmetry group is present we analyse the invariant orbits in the input. We present examples based on rotation groups SO(n) and the unitary group SU(2). Further we find that this method is useful for the classification of complete intersection Calabi-Yau manifolds where it is crucial to identify discrete symmetries on the input space. For this example we present a novel data representation in terms of graphs.

### [Integrability Ex Machina](https://arxiv.org/abs/2103.07475)
#### Sven Krippendorf, Marc Syvaeri, Dieter Luest

Determining whether a dynamical system is integrable is generally a difficult task which is currently done on a case by case basis requiring large human input. Here we propose and test an automated method to search for the existence of relevant structures, the Lax pair and Lax connection respectively. By formulating this search as an optimization problem, we are able to identify appropriate structures via machine learning techniques. We test our method on standard systems of classical integrability and find that we can single out some integrable deformations of a system. Due to the ambiguity in defining a Lax pair our algorithm identifies novel Lax pairs which can be easily verified analytically.

### [Improving Simulations with Symmetry Control Neural Networks](https://arxiv.org/abs/2104.14444)
#### Marc Syvaeri, Sven Krippendorf

The dynamics of physical systems is often constrained to lower dimensional sub-spaces due to the presence of conserved quantities. Here we propose a method to learn and exploit such symmetry constraints building upon Hamiltonian Neural Networks. By enforcing cyclic coordinates with appropriate loss functions, we find that we can achieve improved accuracy on simple classical dynamics tasks. By fitting analytic formulae to the latent variables in our network we recover that our networks are utilizing conserved quantities such as (angular) momentum.
