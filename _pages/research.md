---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

## Research Overview

My research centers on developing and improving statistical methods for evaluating surrogate endpoints and improving clinical trial design, with particular applications to progressive diseases like Alzheimer's disease.

## Research Areas

### Surrogate Endpoint Evaluation
Surrogate endpoints are important tools in clinical research, allowing trials to be conducted with smaller sample sizes and shorter follow-up periods. My work focuses on:
- **Meta-analytic evaluation** of surrogate endpoints with machine learning approaches
- **Information-theoretic methods** based on causal inference
- **Complex surrogate endpoints** in meta-analytic settings
- **Application domains**: vaccine evaluation, progressive disease trials

### Clinical Trial Design for Progressive Diseases
I develop methods to improve the efficiency and interpretability of clinical trials for progressive diseases:
- **Meta-trial components** (Meta TCT) for interpretable treatment effects
- **Multivariate longitudinal outcomes** modeling
- **Alzheimer's disease** as a primary application domain

### Causal Inference and Statistical Methodology
Rigorous causal inference underpins my methodological work:
- **Proportion of treatment effect explained** in mediation analysis
- **Information theory** applications to surrogate evaluation
- **Optimal treatment regime estimation** in practice

## Publications

See below for my publications related to these research areas. You can also find my complete publication list on my [Google Scholar profile](https://scholar-google-com.kuleuven.e-bronnen.be/citations?view_op=list_works&hl=en&user=NXkETpYAAAAJ) and [ORCID](https://orcid.org/0000-0002-4574-8261).

### Publication List

{% include base_path %}
{% for post in site.publications reversed %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}

### Full Publication Details

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## Software

I maintain two R packages available on CRAN and GitHub:

- **[Surrogate](https://cran.r-project.org/package=Surrogate)** (CRAN): A comprehensive suite of methods for evaluating surrogate endpoints, developed collaboratively at I-BioStat, KU Leuven

- **[TCT](https://github.com/florianstijven/TCT)** (GitHub): Methods for progressive disease modeling and treatment effect interpretability

## Collaboration & Contact

Interested in collaborating or discussing research ideas? Please feel free to reach out at [florian.stijven@kuleuven.be](mailto:florian.stijven@kuleuven.be).
