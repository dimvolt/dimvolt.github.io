---
layout: page
permalink: /cv/
title: CV
nav: true
nav_order: 4
description: false
---

<p>
  <a class="btn btn-primary" href="{{ '/assets/pdf/my_cv.pdf' | relative_url }}" download>
    Download CV
  </a>
</p>

London, UK · <a href="mailto:volterasd@gmail.com">volterasd@gmail.com</a> · <a href="https://www.linkedin.com/in/dvolteras/">LinkedIn</a> · <a href="https://github.com/dimvolt">GitHub</a>

## Profile

Computational biologist and machine learning scientist developing predictive models of complex cellular systems from high-dimensional biological data. My research lies at the intersection of modern machine learning and computational biology, spanning generative and representation learning, single-cell biology, dynamical modelling, and probabilistic approaches. I am particularly interested in cellular dynamics, gene regulation and perturbation response, and in how biological structure and experimental design can provide useful inductive biases for ML models. I work closely with experimental scientists to translate biological questions into computational models and testable hypotheses.

## Core Expertise

**Machine Learning &amp; Mathematical Modelling**<br>
Generative modelling · Representation and self-supervised learning · Dynamical models and neural ODEs/SDEs · Bayesian inference · Causal and mechanistic modelling · Stochastic processes · Probabilistic modelling

**Computational &amp; Single-Cell Biology**<br>
Single-cell transcriptomics (scRNA-seq) · Perturbational and interventional data (Perturb-seq, signalling screens) · Gene regulatory networks · Cellular dynamics and trajectory inference · Developmental biology · Lineage tracing · Metabolic RNA labelling

**Programming &amp; Computing**<br>
Python (PyTorch, NumPy, SciPy, Scikit-learn, Scanpy, scVI) · Julia · R · Mathematica · Distributed and multi-GPU training · Large-scale simulation · SLURM/HPC · Linux/Bash · Git/GitHub

## Research Experience

### Postdoctoral Research Fellow · Francis Crick Institute, London

_Developmental Dynamics Laboratory — Dr James Briscoe · Mar 2025 – Present_

- Developed a generative latent-variable model with continuous-time dynamics to learn how gene regulatory networks transform signalling inputs into cell fate outcomes from large-scale, multi-condition single-cell signalling perturbation data. [Related research →]({{ '/research/latent-regulatory-dynamics-of-cell-fate-decisions/' | relative_url }})
- Developed a probabilistic framework for inferring hierarchical lineage relationships from single-cell genomic barcoding data, contributing to an interdisciplinary study of neural tube developmental dynamics (_Nature_, accepted).
- Led development of a stochastic modelling and inference framework for gene regulatory mechanisms from time-resolved single-cell transcriptomics, integrating metabolic RNA labelling and developmental time information. [Related research →]({{ '/research/gene-regulation-from-cellular-variability/' | relative_url }})
- Built and optimised scalable ML and numerical simulation pipelines on HPC infrastructure, including distributed multi-GPU model training.
- Exploring predictive representation-learning approaches for cellular perturbation response from high-dimensional interventional single-cell data. [Related research →]({{ '/research/learning-cellular-responses-to-perturbation/' | relative_url }})

### Postdoctoral Research Associate · Imperial College London

_Computational Molecular Systems Biology Group — Dr Vahid Shahrezaei · Sep 2024 – Feb 2025_

- Developed a stochastic agent-based model to investigate the spatiotemporal dynamics of tumour progression. [Related research →]({{ '/research/modelling-spatial-dynamics-of-glioblastoma-progression/' | relative_url }})
- Contributed computational modelling and quantitative analysis to an interdisciplinary study identifying axonal injury as a targetable driver of glioblastoma progression (_Nature_, 2025).

### PhD Researcher in Computational Biology · Imperial College London

_Computational Molecular Systems Biology &amp; Single-Cell Dynamics Groups — Dr Vahid Shahrezaei &amp; Dr Philipp Thomas · Oct 2020 – Sep 2024_

- Developed stochastic and probabilistic methods to infer gene regulatory mechanisms from high-dimensional single-cell transcriptomics.
- Developed a Bayesian inference framework for genome-wide transcriptional dynamics from time-resolved single-cell RNA sequencing, published in _Cell Systems_. [Related research →]({{ '/research/gene-regulation-from-cellular-variability/' | relative_url }})
- Investigated how cell-to-cell variability and dynamical correlations can reveal modes of gene regulation from single-cell measurements.

## Education

**PhD in Applied Mathematics &amp; Computational Biology** · Imperial College London · 2020 – 2024<br>
Thesis: _Data-driven stochastic modelling of gene regulation_; Roth PhD Scholarship, Department of Mathematics.

**MSc in Applied Mathematics** · Imperial College London<br>
Thesis: _Multiscale approximations of stochastic reaction networks_; focus: mathematical biology, machine learning, stochastic differential equations and Markov processes.

**BSc in Mathematics** · National and Kapodistrian University of Athens<br>
Focus: probability theory, stochastic analysis, Bayesian inference, ODEs and PDEs, and linear algebra.

## Selected Publications

- Volteras, D., Thomas, P., &amp; Shahrezaei, V. (2024). [Global transcription regulation revealed from dynamical correlations in time-resolved single-cell RNA sequencing](https://doi.org/10.1016/j.cels.2024.07.002). _Cell Systems_.
- Boezio, G. L. M., Depotter, J. R. L., Frith, T. J. R., Radley, A., Volteras, D., Strohbuecker, S., et al. (2026). Hierarchical lineage architecture of human and avian spinal cord revealed by single-cell genomic barcoding. _Nature_. Accepted.
- Clements, M., Tang, W., Baronik, Z. F., Ragdale, S., Oria, R., Volteras, D., White, I. J., et al. (2025). [Axonal injury is a targetable driver of glioblastoma progression](https://doi.org/10.1038/s41586-025-09411-2). _Nature_.

## Selected Manuscript in Preparation

Volteras, D., Thomas, P., &amp; Shahrezaei, V. _Inferring causal gene regulatory relationships from time-resolved single-cell transcriptomics with mechanistic machine learning._ Manuscript in preparation.

## Selected Awards

- Best Project Award, AI Hackathon co-organised by Google DeepMind and the Francis Crick Institute (2026)
- Roth PhD Scholarship, Department of Mathematics, Imperial College London (2020)
