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


### [Moduli-dependent Calabi-Yau and SU(3)-structure metrics from Machine Learning](https://arxiv.org/abs/2012.04656)
#### Lara B. Anderson, Mathis Gerdes, James Gray, Sven Krippendorf, Nikhil Raghuram, Fabian Ruehle 

We use machine learning to approximate Calabi-Yau and SU(3)-structure metrics, including for the first time complex structure moduli dependence. Our new methods furthermore improve existing numerical approximations in terms of accuracy and speed. Knowing these metrics has numerous applications, ranging from computations of crucial aspects of the effective field theory of string compactifications such as the canonical normalizations for Yukawa couplings, and the massive string spectrum which plays a crucial role in swampland conjectures, to mirror symmetry and the SYZ conjecture. In the case of SU(3) structure, our machine learning approach allows us to engineer metrics with certain torsion properties. Our methods are demonstrated for Calabi-Yau and SU(3)-structure manifolds based on a one-parameter family of quintic hypersurfaces in P4.

### [GANs for generating EFT models](https://arxiv.org/abs/1809.02612)
#### Harold Erbin, Sven Krippendorf 

We initiate a way of generating effective field theories (EFT) models by the computer, satisfying both experimental and theoretical constraints. We use Generative Adversarial Networks (GAN) and display generated instances which go beyond the examples known to the machine during training. As a starting point, we apply this idea to the generation of supersymmetric field theories with a single field. We find cases where the number of minima in the generated scalar potential is different from values found in the training data. We comment on potential further applications of this framework.
