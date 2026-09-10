---
layout: page
title: Learning cellular responses to perturbation
description: Exploring predictive representation learning for modelling cellular responses to genetic interventions.
permalink: /research/learning-cellular-responses-to-perturbation/
importance: 3
featured: false
research_section: exploratory
---

_Exploratory research · Ongoing · Solo project_

<span class="research-keyword">predictive representation learning</span> · <span class="research-keyword">self-supervised learning</span> · <span class="research-keyword">perturbations</span> · <span class="research-keyword">Perturb-seq</span> · <span class="research-keyword">single-cell transcriptomics</span>

## Motivation

Predicting how cells respond to genetic interventions is a central challenge in biology. Perturb-seq experiments combine CRISPR-based perturbations with single-cell transcriptomic measurements, offering a way to study cellular responses across control and perturbed populations. Better predictive models could help reveal principles of gene regulation and support more systematic efforts to understand and manipulate cellular systems.

## The idea

This project explores perturbation prediction as a predictive representation learning problem, rather than one that requires generating a cell's complete molecular state. The aim is to learn compact representations of cellular state and predict how they change under genetic interventions.

I am investigating whether structured latent representations and biologically motivated inductive biases can improve generalisation while retaining a meaningful connection to the underlying biology and experimental setting.

The longer-term goal is to explore whether such representations could form the basis of a latent “world model” of cellular perturbation response: one that can generalise beyond observed interventions and provide interpretable representations of how perturbations affect gene regulatory programmes. More broadly, the project asks whether predictive representation learning can bridge flexible, data-driven perturbation models with structured mechanistic models of gene regulation.

## Current direction

An initial modelling framework is developed, and experimentation is ongoing. A central question currently is which forms of biological structure genuinely improve generalisation in perturbation prediction, and when they provide a useful advantage over less structured approaches.
