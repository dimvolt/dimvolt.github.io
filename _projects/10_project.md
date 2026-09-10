---
layout: page
title: Learning Cellular Responses to Perturbation
description: Exploring predictive representation learning for modelling cellular responses to genetic interventions.
permalink: /research/learning-cellular-responses-to-perturbation/
importance: 3
featured: false
research_section: exploratory
---

_Exploratory research · Ongoing · Solo project_

<span class="research-keyword">Predictive Representation Learning</span> · <span class="research-keyword">Perturb-seq</span> · <span class="research-keyword">Self-Supervised Learning</span> · <span class="research-keyword">Perturbational Biology</span> · <span class="research-keyword">Single-Cell Transcriptomics</span>

## Motivation

Predicting how cells respond to genetic interventions is a central challenge in biology. Perturb-seq experiments combine CRISPR-based perturbations with single-cell transcriptomic measurements, offering a way to study cellular responses across control and perturbed populations. Better predictive models could help reveal principles of gene regulation and support more systematic efforts to understand and manipulate cellular systems.

## The idea

This project explores perturbation prediction as a predictive representation learning problem, rather than one that must directly generate a cell's complete molecular state. The aim is to learn compact representations of cellular state and model how those representations change under genetic intervention.

The working hypothesis is that structured latent representations and biologically motivated inductive biases can make these predictions more useful and robust. The focus is on identifying representations that capture meaningful aspects of cellular response while retaining a clear connection to the biology and experimental setting.

## Current direction

An initial PyTorch framework is in place, and experimentation is ongoing. A central question is which forms of biological structure genuinely improve generalisation in perturbation prediction, and when they provide a useful advantage over less structured approaches.
