---
title: The vast String Theory Landscape
layout: page
description: 
---


String theory is a wonderful framework for a quantum theory of all known interactions. What keeps puzzling me is whether we can find a way to test string theory experimentally? Although there are many possible signatures (e.g. axion-like particles), it is unclear at which scale below the Planck scale (~10^18 GeV) we can expect generic (~guaranteed) signatures arising from string theory. For example, a guaranteed signature of low-energy supersymmetry which addresses the electroweak hierarchy problem, is that there are new particles around the TeV scale (likely above the energy reach of the LHC).

To get an idea of what are the typical signatures we need to study samples from the set of consistent string theory solutions. There are two major hurdles:

1) How to construct consistent string theory solutions?

2) How to sample the vast set of solutions even in a class of string theory solutions?

Although traditional techniques have been applied to this problem for decades with steady progress (see my publication list for work in this direction), numerical methods seem inevitable in sampling this set efficiently. Recent ML advances in sampling from high-dimensional distributions (e.g. image sampling via GANs and Invertible NNs/flows) seem a promising new direction and we are working on using these techniques to gain new insights on our string theory solutions.

We have used RL and genetic algorithms to tackle the inverse problem of the string landscape, i.e. to sample vacua with particular phenomenological properties. We demonstrate that these methods can reveal novel structures (symmetries) in such string theory solutions.


### [Moduli-dependent Calabi-Yau and SU(3)-structure metrics from Machine Learning](https://arxiv.org/abs/2012.04656)
#### Lara B. Anderson, Mathis Gerdes, James Gray, Sven Krippendorf, Nikhil Raghuram, Fabian Ruehle 

We use machine learning to approximate Calabi-Yau and SU(3)-structure metrics, including for the first time complex structure moduli dependence. Our new methods furthermore improve existing numerical approximations in terms of accuracy and speed. Knowing these metrics has numerous applications, ranging from computations of crucial aspects of the effective field theory of string compactifications such as the canonical normalizations for Yukawa couplings, and the massive string spectrum which plays a crucial role in swampland conjectures, to mirror symmetry and the SYZ conjecture. In the case of SU(3) structure, our machine learning approach allows us to engineer metrics with certain torsion properties. Our methods are demonstrated for Calabi-Yau and SU(3)-structure manifolds based on a one-parameter family of quintic hypersurfaces in P4.

### [GANs for generating EFT models](https://arxiv.org/abs/1809.02612)
#### Harold Erbin, Sven Krippendorf 

We initiate a way of generating effective field theories (EFT) models by the computer, satisfying both experimental and theoretical constraints. We use Generative Adversarial Networks (GAN) and display generated instances which go beyond the examples known to the machine during training. As a starting point, we apply this idea to the generation of supersymmetric field theories with a single field. We find cases where the number of minima in the generated scalar potential is different from values found in the training data. We comment on potential further applications of this framework.

### [Probing the Structure of String Theory Vacua with Genetic Algorithms and Reinforcement Learning](https://arxiv.org/abs/2111.11466)
#### Alex Cole, Sven Krippendorf, Andreas Schachner, Gary Shiu 

Identifying string theory vacua with desired physical properties at low energies requires searching through high-dimensional solution spaces - collectively referred to as the string landscape. We highlight that this search problem is amenable to reinforcement learning and genetic algorithms. In the context of flux vacua, we are able to reveal novel features (suggesting previously unidentified symmetries) in the string theory solutions required for properties such as the string coupling. In order to identify these features robustly, we combine results from both search methods, which we argue is imperative for reducing sampling bias.

### [Revealing systematics in phenomenologically viable flux vacua with reinforcement learning](https://arxiv.org/abs/2107.04039)
#### Sven Krippendorf, Rene Kroepsch, Marc Syvaeri

The organising principles underlying the structure of phenomenologically viable string vacua can be accessed by sampling such vacua. In many cases this is prohibited by the computational cost of standard sampling methods in the high dimensional model space. Here we show how this problem can be alleviated using reinforcement learning techniques to explore string flux vacua. We demonstrate in the case of the type IIB flux landscape that vacua with requirements on the expectation value of the superpotential and the string coupling can be sampled significantly faster by using reinforcement learning than by using metropolis or random sampling. Our analysis is on conifold and symmetric torus background geometries. We show that reinforcement learning is able to exploit successful strategies for identifying such phenomenologically interesting vacua. The strategies are interpretable and reveal previously unknown correlations in the flux landscape.
