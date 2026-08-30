---
layout: page
title: Research
permalink: /research/
---

Our research asks two complementary questions: what can physics teach us about
learning systems, and what can modern machine learning reveal about fundamental
physics? We combine mathematical and theoretical analysis with computational
experiments and automated search.

## Physics of Learning

We treat learning systems as physical and mathematical objects. We investigate
how data selection, optimisers and architectures shape learning dynamics,
internal representations and scaling behaviour. Our approach combines ideas
from statistical and theoretical physics with controlled numerical experiments:
the aim is not only to observe scaling laws, but to understand the mechanisms
behind them and turn that understanding into better learning systems.

Current work includes collective descriptions of neural-network training and
the mechanisms behind neural scaling.

Selected work:

- [Spectral Reach: Understanding Neural Scaling as Progress into the Spectral Tail (ICML 2026)](https://arxiv.org/abs/2605.31244)
- [Beyond scaling curves: internal dynamics of neural networks through the NTK lens](https://doi.org/10.1088/2632-2153/ae4442)
- [Collective variables of neural networks: empirical time evolution and scaling laws](https://doi.org/10.1088/2632-2153/adee76)

## Machine learning for fundamental physics

We develop machine-learning and agentic systems for problems in quantum field
theory, particle physics and string theory. This is a natural continuation of
our earlier work on discovering symmetries, dualities and integrable structure.
[Detecting Symmetries with Neural Networks](https://arxiv.org/abs/2003.13679)
established the broad idea of learning mathematical structure from data;
[Integrability Ex Machina](https://arxiv.org/abs/2103.07475) showed how an
automated search could recover precise theoretical structures. Today's
agentic systems extend this direction by exploring executable representations,
algorithms and physical models at scale.

### Featured project: scattering amplitudes as programs

With Yi Gu, we treat scattering-amplitude calculations as executable programs
and use self-evolving program search to find more efficient and revealing
representations. The search moves between ideas from amplitude theory—recursion,
symmetry, basis reduction and shared computation—and combines them into new
algorithms. [Read the paper](https://arxiv.org/abs/2607.21629) or
[explore the code and search trajectories](https://github.com/YiGu310/scattering-amplitudes-program-search).

### String vacua at scale

[JAXVacua](https://jaxvacua.readthedocs.io/) is infrastructure for constructing
and exploring large ensembles of string vacua efficiently. Developed over
several years with Andreas Schachner and collaborators, it uses automatic
differentiation, compilation and parallelisation in JAX to make previously
inaccessible regions of the Type IIB flux landscape computationally tractable.
[Read the foundational paper](https://arxiv.org/abs/2306.06160).

With Zhimei Liu, we use conditional generative models to solve the inverse
problem: rather than sampling vacua first and filtering afterwards, we generate
flux configurations targeted at desired physical properties.
[Read the paper](https://arxiv.org/abs/2506.22551).

### Numerical Calabi–Yau geometry

Ricci-flat Calabi–Yau metrics solve nonlinear geometric differential equations
but are rarely known explicitly. Our numerical work uses machine learning to
approximate these metrics across families of geometries, including their
dependence on complex-structure moduli. This makes geometric quantities needed
for string compactifications accessible to computation.

- [Moduli-dependent Calabi–Yau and SU(3)-structure metrics from Machine Learning](https://arxiv.org/abs/2012.04656)
- [CYJAX: A package for Calabi–Yau metrics with JAX](https://arxiv.org/abs/2211.12520)

### Verified and reusable physics

We are exploring formal verification through
[PhysLib](https://github.com/leanprover-community/physlib), the community Lean
library for physics. Formalisation does not by itself establish that a physical
model is meaningful, but it makes definitions, assumptions and logical steps
explicit and machine-checkable. In recent work with Joseph Tooby-Smith, we
developed reusable PhysLib infrastructure for a certified classification
problem in SU(5) model building.
[Read the preprint](https://arxiv.org/abs/2603.28406).

## Further applications in cosmology and phenomenology

Alongside these two core research directions, we apply machine-learning and
data-intensive methods to selected problems in cosmology and particle-physics
phenomenology. With Nina Elmer, we study how errors in neural-network outputs
can be quantified and when those outputs can be trusted, particularly in
particle-physics applications.

Continuing collaborations include cosmological inference with Kai Lehman and
eROSITA cluster science with Silas Zelmer. Earlier work in this strand has also
addressed gravitational-wave signals and searches for new particles such as
axion-like particles.

Selected work:

- [Learning optimal summary statistics of galaxy catalogs with SBI](https://doi.org/10.1088/1475-7516/2025/12/032)
- [A machine-learning approach to inferring galaxy-cluster masses from eROSITA X-ray images](https://arxiv.org/abs/2305.00016)
- [Updated bounds on axion-like particles from X-ray observations](https://arxiv.org/abs/2108.04827)

For talks and discussions across these areas, see the
[DAMTP Data Intensive Science Seminar](https://talks.cam.ac.uk/show/index/197992/)
and the former [Physics Meets ML initiative](http://physicsmeetsml.org/).

Interested in joining us or seeking fellowship hosting? See
[Opportunities]({{ '/opportunities/' | relative_url }}).
