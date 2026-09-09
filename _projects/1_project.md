---
layout: page
title: Learning Gene Regulation from Cellular Variability
description: Inferring genome-wide transcriptional dynamics from time-resolved single-cell RNA sequencing.
permalink: /research/gene-regulation-from-cellular-variability/
importance: 1
featured: true
---

Single-cell transcriptomics records substantial cell-to-cell variability, but a single measurement provides only a partial view of the dynamic processes that generated it. This project uses time-resolved single-cell RNA sequencing to ask what that variability can reveal about transcriptional regulation.

## The question

Can temporal correlations in single-cell measurements identify the mechanisms that control transcription dynamics? More specifically, can they distinguish how transcriptional bursting and mRNA degradation change across the cell cycle at transcriptome-wide scale?

## The challenge

Observed RNA counts combine biological stochasticity with technical variation. They are also shaped by changing cell size and cell-cycle state. These sources of variation make it difficult to infer kinetic mechanisms from static snapshots alone, and a useful approach must account for them without losing the scale needed for genome-wide analysis.

## The approach

The work develops a stochastic gene-expression model with cell size- and cell cycle-dependent rates in growing and dividing cells. It uses the temporal information supplied by metabolic-labeling protocols and cell-cycle reporters, alongside a parallel, scalable approximate Bayesian computation method that corrects for technical variation. Bayesian model selection is then used to compare candidate mechanisms of regulation.

## What we found

The analysis quantifies burst frequency, burst size, and mRNA degradation rate across the cell cycle at transcriptome-wide scale. It identifies evidence for transcription rates that scale with cell size and reveals waves of transcriptional regulation across the cell cycle-dependent transcriptome.

This project is described in the open-access paper [*Global transcription regulation revealed from dynamical correlations in time-resolved single-cell RNA sequencing*](https://doi.org/10.1016/j.cels.2024.07.002), published in *Cell Systems* (2024).
