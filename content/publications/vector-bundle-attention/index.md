---
title: "VBA: Vector Bundle Attention for Intrinsically Geometric Representation Learning"
date: 2026-06-25
authors:
  - me
  - Xianfang Sun
  - You Zhou
publication_types:
  - paper-conference
publication:
  name: International Conference on Machine Learning
  short_name: "[ICML 2026 · OpenReview](https://openreview.net/forum?id=nQ4iLQtsCF)"
abstract: >
  Vector Bundle Attention redefines attention as an intrinsic geometric
  operator. Each token combines a base-manifold coordinate with a fibre feature,
  while parallel transport aligns features across local coordinate systems
  before similarity is computed. The method is evaluated on single-cell RNA
  sequencing, spatial transcriptomics, and 3D point-cloud benchmarks, together
  with analyses of invariance and perturbation stability.
summary: >
  An intrinsic attention mechanism that aligns features with parallel transport
  before comparing them across a learned geometric space.
tags:
  - Geometric Deep Learning
  - Attention
  - Vector Bundles
  - Scientific Machine Learning
featured: true
peer_reviewed: true
open_access: true
---

## Overview

VBA-Transformer embeds geometry inside the attention operation itself. Rather
than adding geometric information as an external bias, it models each token as
a base coordinate paired with a fibre feature and uses parallel transport to
align local feature frames before computing attention.

## Applications

- Single-cell RNA sequencing
- Spatial transcriptomics
- 3D point-cloud representation learning

The accompanying analysis studies invariance, perturbation stability, and the
behaviour of the learned transport mechanism.

[Read the paper on OpenReview](https://openreview.net/forum?id=nQ4iLQtsCF)
