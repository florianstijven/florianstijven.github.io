---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

## Research Overview

My doctoral research centers on developing and improving statistical methods for evaluating surrogate endpoints with applications in, among other areas, oncology and vaccine studies. 
I am currently also doing research on methods for multivariate longitudinal data where the underlying processes are irreversible, with applications in the modelling of aging and neuro-degenerative diseases. 

## Research Areas

### Surrogate Endpoint Evaluation

In clinical trials, the primary endpoint is ideally a clinical endpoint (i.e., an endpoint that reflects how a patient feels, functions, or survives) as such endpoints are most relevant to patients. They may be difficult to use as primary endpoint, however, because they may require a long follow up or be expensive to measure. For instance, in clinical trials on early-stage breast cancer, using overall survival as primary endpoint may require an unrealistically long follow up. 

Surrogate endpoints are biomarkers that are less relevant to patients and clinicians, but which are easier to measure (e.g., requiring less follow-up time). Clinical trials can, therefore, be conducted more efficiently if a surrogate endpoint replaces a clinical endpoints as primary endpoint. However, before surrogate endpoints can be used as primary endpoints, they should be evaluated. 
Such an evaluation firstly involves scientific arguments: Are treatment effects on the surrogate reasonably likely to translate to treatment effects on the clinical endpoint?
Secondly, the surrogate should be evaluated statistically. 

My work focuses on the statistical evaluation of surrogate endpoints. I have worked on the following topics:
- Meta-analytic evaluation of complex surrogate endpoints with machine learning approaches [[preprint](https://arxiv.org/abs/2509.01737)]
- Proportion of treatment effect explained as a measure of surrogacy [[paper](https://journals.sagepub.com/doi/full/10.1177/09622802241259177)]
- Evaluation of time-to-event surrogates endpoint for time-to-event clinical endpoints (typically overall survival) using data from a single clinical trial [[paper](https://link.springer.com/article/10.1007/s10985-024-09638-7)]

### Multivariate Longitudinal Data with Monotonicity Constraints

Irreversible processes are studied in many areas of medicine:
- **Neuro-degenerative diseases** such as Alzheimer's disease and Parkinson's disease, where cognitive and motor decline is progressive.
- **Aging processes** where biological markers progressively deteriorate over the lifespan.

Measures of the underlying processes are expected to evolve monotonically as a function of time. Moreover, these processes can be measured in many different ways—clinical scales, blood markers, and imaging markers—each capturing different aspects of disease progression. Hence, a complete study of such irreversible processes involves the measurement of multivariate outcomes repeatedly over time, where the evolution is monotonic. This leads to multivariate longitudinal data with monotonicity constraints. 

Few statistical methods are available for (multivariate) longitudinal data with monotonicity constraints. Recent work includes the work of Lars Lau Raket [[paper1](https://onlinelibrary.wiley.com/doi/full/10.1002/sim.9581)] [[paper2](https://www.frontiersin.org/journals/big-data/articles/10.3389/fdata.2020.00024/full)] where non-linear mixed models are used to model monotonic disease progression. 
I have contributed to this area by developing a semi-parametric two-stage method for estimating effects of disease-modifying treatments in terms of slowing disease progression [[preprint](https://doi.org/10.1101/2024.05.31.24307898)].

My goal is to develop a general framework for modelling multivariate longitudinal data with monotonicity constraints. This includes:
- Defining assumption-lean causal target parameters, characterizing the required identifying assumptions, and developing non-parametric estimators for these parameters.
- Developing a semi-parametric model for parsimoniously modelling the slowing effects of certain exposures on the underlying irreversible processes.

### Other Research

I have also worked on the estimation of optimal treatment regimes in the treatment of depression [paper](https://academic.oup.com/biometrics/article/81/1/ujaf026/8087929).

I am currently involved in research on statistical methods for distribution-valued outcomes, with applications in HIV trials. 

## Software

I maintain two R packages available on CRAN and GitHub:

- **[Surrogate](https://cran.r-project.org/package=Surrogate)** (CRAN): A comprehensive suite of methods for evaluating surrogate endpoints, developed collaboratively at I-BioStat, KU Leuven

- **[TCT](https://github.com/florianstijven/TCT)** (GitHub): Methods for progressive disease modeling and treatment effect interpretability

## Collaboration & Contact

Interested in collaborating or discussing research ideas? Please feel free to reach out at [florian.stijven@kuleuven.be](mailto:florian.stijven@kuleuven.be).
