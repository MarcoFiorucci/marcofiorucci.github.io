---
layout: page
title: "RankAlign: Vision-Language Representation Alignment via Rank Transformation"
description: "Vision-Language Representation Alignment via Rank Transformation (NeurIPS 2026)"
img: assets/img/rankalign/pipeline.png
importance: 1
category: work
---

<script>
  // Forza in modo permanente la modalità chiara su questa pagina
  localStorage.setItem('theme', 'light');
  document.documentElement.setAttribute('data-theme', 'light');
  document.body.classList.remove('dark');
  document.body.classList.add('light');
</script>

<div style="text-align: center; margin-top: 1rem; margin-bottom: 2rem;">
  <p style="font-size: 1.15rem; font-weight: 600; color: #000000 !important; margin-bottom: 0.5rem;">
    Enzhe Zhao<sup>1,*</sup>, &nbsp;
    Marco Fiorucci<sup>1,*</sup>, &nbsp;
    Lamberto Ballan<sup>1</sup>
  </p>
  <p style="font-size: 1rem; color: #000000 !important; margin-bottom: 0.3rem;">
    <sup>1</sup> University of Padua &nbsp;&nbsp;&nbsp;&nbsp; <sup>2</sup> Harbin Institute of Technology
  </p>
  <p style="font-size: 0.9rem; color: #000000 !important;">
    <sup>*</sup> Equal contribution &nbsp;|&nbsp; <strong>NeurIPS 2026</strong>
  </p>
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

* [**Paper (arXiv)**](https://arxiv.org/abs/2610.31145)
* [**Code (GitHub)**](https://github.com/marcofiorucci)

## Citation

```bibtex
@inproceedings{zhao2026rankalign,
  title={RankAlign: Vision-Language Representation Alignment via Rank Transformation},
  author={Zhao, Enzhe and Fiorucci, Marco and Ballan, Lamberto},
  booktitle={Advances in Neural Information Processing Systems (NeurIPS)},
  year={2026}
}
