---
title: "Validating uncertainty propagation approaches for two-stage Bayesian spatial models using simulation-based calibration"
collection: publications
category: arxiv
permalink: /publication/2025-02-26-paper-title-number-4
excerpt: ''
date: 2025-02-26
venue: 'arXiv'
paperurl: 'https://academicpages.github.io/files/paper7.pdf'
citation: 'Villejo, S. J., Martino, S., Illian, J., Ryan, W., & Lindgren, F. (2025). Validating uncertainty propagation approaches for two-stage Bayesian spatial models using simulation-based calibration. arXiv preprint arXiv:2502.18962.'
---

This work tackles the problem of uncertainty propagation in two-stage Bayesian models, with a focus on spatial applications. A two-stage modeling framework has the advantage of being more computationally efficient than a fully Bayesian approach when the first-stage model is already complex in itself, and avoids the potential problem of unwanted feedback effects. Two ways of doing two-stage modeling are the crude plug-in method and the posterior sampling method. The former ignores the uncertainty in the first-stage model, while the latter can be computationally expensive. This paper validates the two aforementioned approaches and proposes a new approach to do uncertainty propagation, which we call the  uncertainty method, implemented using the Integrated Nested Laplace Approximation (INLA). We validate the different approaches using the simulation-based calibration method, which tests the self-consistency property of Bayesian models. Results show that the crude plug-in method underestimates the true posterior uncertainty in the second-stage model parameters, while the resampling approach and the proposed method are correct. We illustrate the approaches in a real life data application which aims to link relative humidity and Dengue cases in the Philippines for August 2018.