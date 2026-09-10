---
layout: page
title: Learning gene regulation from cellular variability
description: Inferring genome-wide transcriptional dynamics from time-resolved single-cell transcriptomics.
permalink: /research/gene-regulation-from-cellular-variability/
importance: 1
featured: true
---

Single-cell transcriptomics (scRNA-seq) records substantial cell-to-cell variability, but a single snapshot measurement provides only a partial view of the dynamic processes that generated it. This project uses time-resolved single-cell RNA sequencing to ask what that variability can reveal about transcriptional regulation.

<span class="research-keyword">single-cell transcriptomics</span> · <span class="research-keyword">Bayesian inference</span> · <span class="research-keyword">stochastic modelling</span> · <span class="research-keyword">gene regulation</span>

## The question

Can covariation patterns in single-cell measurements identify the mechanisms that control transcription dynamics? More specifically, can they distinguish how transcriptional bursting and mRNA degradation change across the cell cycle at transcriptome-wide scale?

## The challenge

Observed mRNA count distributions arise from both biological stochasticity with technical variation. They are also determined by global cellular states, such as cell size and cell cycle state. These sources of variation make it difficult to infer transcriptional kinetic mechanisms from static snapshots alone. A useful mechanistic model must account for all those sources, without losing the scale needed for genome-wide analysis.

## The approach

The work develops a stochastic gene expression model with cell size- and cell cycle-dependent kinetic rates in growing and dividing cells. It uses temporal information supplied by metabolic labelling protocols and cell cycle reporters, alongside a parallel, scalable approximate Bayesian computation method that corrects for technical variation. Bayesian model selection is then used to compare candidate mechanisms of regulation.

## What we found

The analysis quantifies burst frequency, burst size, and mRNA degradation rate across the cell cycle at transcriptome-wide scale. It identifies evidence for transcription rates that scale with cell size and reveals waves of transcriptional regulation across the cell cycle-dependent transcriptome.

This project is described in the open-access paper [_Global transcription regulation revealed from dynamical correlations in time-resolved single-cell RNA sequencing_](https://doi.org/10.1016/j.cels.2024.07.002), published in _Cell Systems_ (2024).
