---
layout: page
title: "RankAlign: Vision-Language Representation Alignment via Rank Transformation"
description: "Vision-Language Representation Alignment via Rank Transformation (NeurIPS 2026)"
img: assets/img/rankalign/pipeline.png
importance: 1
category: work
---

<style>
  /* Forza i link dell'autore e il testo del titolo in nero puro */
  body.light .post h1.post-title,
  body.light .post a {
    color: #000000 !important;
  }
  
  /* Stili aggiuntivi per l'area degli autori */
  .author-list {
    font-size: 1.15rem;
    margin: 1rem 0 0.5rem 0;
  }
  .affiliations {
    color: #555; /* Un grigio scuro per le affiliazioni per contrasto */
    font-size: 0.95rem;
    margin-bottom: 2rem;
  }
</style>

<div class="author-list text-center">
  <a href="https://enzhezhao.github.io/"><strong>Enzhe Zhao</strong></a><sup>*</sup>, 
  <a href="https://marcofiorucci.github.io/"><strong>Marco Fiorucci</strong></a><sup>*</sup>, 
  <a href="https://www.math.unipd.it/~ballan/"><strong>Lamberto Ballan</strong></a>
</div>

<div class="affiliations text-center">
  University of Padua, Italy<br>
  <small><sup>*</sup> Equal contribution</small>
</div>

## Abstract

While the Platonic Representation Hypothesis posits that vision and language models converge toward compatible latent geometries, recovering class-level correspondences between unpaired modalities without cross-modal supervision remains challenging. Existing relational matching methods compare within-modality similarity kernels directly, although the same semantic structure may be represented through different numerical parameterizations across modalities. We propose **RankAlign**, a rank-based normalization strategy for class-level unpaired vision-language matching. RankAlign transforms each within-modality similarity kernel into an ordinal relational representation before permutation matching, while leaving the correspondence space and matching solver unchanged. The resulting representation is invariant to strictly increasing reparameterizations of similarity values while preserving the ordinal structure used for matching. We provide exact-recovery and stability guarantees that characterize correspondence recovery under both exact and partial ordinal agreement. Experiments across diverse frozen vision and language encoders and multiple datasets demonstrate improved and more stable class-level correspondence recovery, including under label corruption and domain shift.

## Overview

Overview of the RankAlign framework architecture and representation alignment pipeline.

<div class="row justify-content-sm-center my-4">
  <div class="col-sm-10 text-center">
    {% include figure.liquid path="assets/img/rankalign/pipeline.png" title="RankAlign Pipeline Overview" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
<div class="caption text-center">
  <strong>Figure 1:</strong> RankAlign framework for Vision-Language Representation Alignment via Rank Transformation.
</div>

## Resources

* [**Paper (arXiv)**](https://arxiv.org/)
* [**Code (GitHub)**](https://github.com/marcofiorucci)

## Citation

```bibtex
@inproceedings{zhao2026rankalign,
  title={RankAlign: Vision-Language Representation Alignment via Rank Transformation},
  author={Zhao, Enzhe and Fiorucci, Marco and Ballan, Lamberto},
  booktitle={Advances in Neural Information Processing Systems (NeurIPS)},
  year={2026}
}
