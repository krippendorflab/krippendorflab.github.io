---
title: Data Driven Phenomenology for Beyond the Standard Model Physics
layout: page
description: 
---
At a very coarse level particle physics phenomenology is about writing down effective field theories to describe more and more aspects of the Universe we observe, and to find clever ways of testing these models.

The way we typically come up with new models seems rather baroque as we use more or less the same tools of well-defined building blocks for decades (symmetries, extra-dimensions, power-law scalings, etc.) which provide us with a "handful" of models to examine and use. I have done exactly this type of physics in the past (see my publication list).

This is at first sight in contradiction with the success of deep over-parameterized neural networks which show remarkable performance on many but clearly not all tasks. This contradiction due to over-parameterization can be overcome when we know what the neural network is calculating.

By trying to figure out which features your ML algorithm is using and which simple (i.e. compressed into few parameters) models are behind the solutions found by a neural network, my aim is to identify more accurate phenomenological models and to find new ways of testing existing models.

In particular, this is about constraining axion-like particles, one promising dark matter candidate, and this is about improving phenomenological models used in astrophysics to sharpen our predictions on &Lambda;CDM cosmological parameters.


### [The eROSITA Final Equatorial-Depth Survey (eFEDS): A Machine Learning Approach to Infer Galaxy Cluster Masses from eROSITA X-ray Images](https://arxiv.org/abs/2305.00016)
#### Sven Krippendorf, Nicolas Baron Perez, Esra Bulbul, Melih Kara, Riccardo Seppi, Johan Comparat, Emmanuel Artis, Y. Emre Bahar, Christian Garrel, Vittorio Ghirardini, Matthias Kluge, Ang Liu, Miriam E. Ramos-Ceja, Jeremy Sanders, Xiaoyuan Zhang, Marcus Brüggen, Sebastian Grandis, Jochen Weller

We develop a neural network based pipeline to estimate masses of galaxy clusters with a known redshift directly from photon information in X-rays. Our neural networks are trained using supervised learning on simulations of eROSITA observations, focusing in this
paper on the Final Equatorial Depth Survey (eFEDS). We use convolutional neural networks which are modified to include additional
information of the cluster, in particular its redshift. In contrast to existing work, we utilize simulations including background and point
sources to develop a tool which is usable directly on observational eROSITA data for an extended mass range from group size halos to
massive clusters with masses. Using this method, we are able to provide for the first time neural
network mass estimation for the observed eFEDS cluster sample from Spectrum-Roentgen-Gamma/eROSITA observations and we
find consistent performance with weak lensing calibrated masses. In this measurement, we do not use weak lensing information and
we only use previous cluster mass information which was used to calibrate the cluster properties in the simulations. When compared
to simulated data, we observe a reduced scatter with respect to luminosity and count-rate based scaling relations. We comment on the
application for other upcoming eROSITA All-Sky Survey observations.

### [Accelerating the search for Axion-Like Particles with machine learning](https://arxiv.org/abs/1907.07642)
#### Francesca Day, Sven Krippendorf

Machine learning (ML) techniques have been applied with tremendous success in many areas of physics. In this work, we use ML to place bounds on the coupling between photons and axion-like particles (ALPs). This coupling causes ALPs and photons to interconvert in the presence of a background magnetic field. This would lead to modulations in the spectra of point sources shining through the magnetic fields of galaxy clusters. This effect has already been used to place world-leading bounds on the ALP-photon coupling using conventional statistical methods. We train ML classification algorithms on simulated spectra from the Chandra X-ray telescope for a range of point sources and ALP-photon couplings. We then use the response of these algorithms to the real Chandra spectra to place bounds on ALP-photon interactions. We obtain bounds at a similar level to those based on other techniques, but find improvements on an individual source basis. We expect such search techniques to become increasingly important for ALP searches with future telescopes that will offer substantially higher energy resolution.

### [Updated Bounds on Axion-Like Particles from X-ray Observations](https://arxiv.org/abs/2108.04827)
#### Simon Schallmoser, Sven Krippendorf, Francesca Chadha-Day, Jochen Weller

In this work we revisit five different point sources within or behind galaxy clusters in order to constrain the coupling constant between axion-like particles (ALPs) and photons. We use three distinct machine learning (ML) techniques and compare our results with a standard chi-squared  analysis. For the first time we apply approximate Bayesian computation to searches for ALPs and find consistently good performance across ML classifiers. Further, we apply more realistic 3D magnetic field simulations of galaxy clusters and compare our results with previously used 1D simulations. We find constraints on the ALP-photon coupling at the level of state-of-the-art bounds with g_{a\gamma\gamma}< 0.6 10^{-12}GeV^{-1}, hence improving on previous constraints obtained from the same observations.

