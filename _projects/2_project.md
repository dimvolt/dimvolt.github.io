---
layout: page
title: Learning latent regulatory dynamics of cell fate decisions
description: A generative modelling framework for learning how gene regulatory networks transform external signals into developmental cell fate outcomes.
permalink: /research/latent-regulatory-dynamics-of-cell-fate-decisions/
importance: 2
featured: true
---

_Ongoing postdoctoral research · Work in progress_

`generative ML` · `representation learning` · `latent dynamical systems` · `single-cell transcriptomics` · `perturbations`

## The question

How do extracellular signalling environments shape the regulatory programmes that guide cells towards distinct developmental fates? The aim is to learn a compact, interpretable account of this transformation: from changing inputs, through regulatory dynamics, to observed cell state outcomes.

## The opportunity

Single-cell transcriptomics can now measure cellular populations across multiple signalling and perturbation contexts. Taken together, these measurements provide a rich view of how developmental trajectories change with their environment. They also pose a difficult modelling problem: each condition is high-dimensional and heterogeneous, while the underlying regulatory processes evolve over time and are only observed indirectly.

## The modelling approach

This project develops a generative latent variable model with continuous-time dynamics. The model is trained jointly across multiple signalling conditions to connect external inputs with latent regulatory processes and gene expression observations. It learns interpretable gene modules while incorporating biologically motivated structural constraints, balancing expressive representation learning with a model whose components can be related back to regulatory programmes.

## Current direction

The work is currently focused on developing and evaluating the framework across observed and held-out signalling conditions. The broader goal is to determine when a learned representation of regulatory dynamics can provide a useful, interpretable basis for comparing developmental responses across environments.
