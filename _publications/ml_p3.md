---
title: "Attention-based Neural Network Emulators for Multi-Probe Data Vectors Part III: Modeling The Next Generation Surveys"
collection: publications
category: manuscripts
permalink: /publication/attention-emulators-part-3
excerpt: 'Machine learning can accelerate cosmological inferences that involve many sequential evaluations of computationally expensive data vectors. Previous works in this series have examined how machine learning architectures impact emulator accuracy and training time for optical shear and galaxy clustering 2-point function. In this final manuscript, we explore neural network performance when emulating Cosmic Microwave Background temperature and polarization power spectra. We maximize the volume of applicability in the parameter space of our emulators within the standard Λ-cold-dark-matter model while ensuring that errors are below cosmic variance. Relative to standard multi-layer perceptron architectures, we find the dot-product-attention mechanism reduces the number of outliers among testing cosmologies, defined as the fraction of testing points with Δχ2>0.2 relative to \textsc{CAMB} outputs, for a wide range of training set sizes. Such precision enables attention-based emulators to be directly applied to real data without requiring any additional correction via importance sampling. Combined with pre-processing techniques and optimized activation and loss functions, attention-based models can meet the precision criteria set by current and future CMB and lensing experiments. For each of Planck, Simons Observatory, CMB S4, and CMB HD, we find the fraction of outlier points to be less than 10% with around 2×105 to 4×105 training data vectors. We further explore the applications of these methods to supernova distance, weak lensing, and galaxy clustering, as well as alternative architectures and pre-processing techniques. '
date: 2025-5-28
venue: 'arXiv'
paperurl: '    
https://doi.org/10.48550/arXiv.2505.22574'
#bibtexurl: 'http://evansaraivanov.github.io/files/2023-baryons.bib'
---

