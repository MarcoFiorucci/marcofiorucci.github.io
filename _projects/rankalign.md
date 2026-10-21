---
layout: page
title: "RankAlign: Vision-Language Representation Alignment via Rank Transformation"
description: "Vision-Language Representation Alignment via Rank Transformation (NeurIPS 2026)"
img: assets/img/rankalign/pipeline.png
importance: 1
category: work
---

<div class="text-center my-4">
  <!-- Autori -->
  <div style="font-size: 1.2rem; font-weight: 600; color: #000000 !important; margin-bottom: 0.5rem;">
    <a href="https://enzhezhao.github.io/" style="color: #000000 !important; text-decoration: none;">Enzhe Zhao</a><sup style="color: #000000 !important;">1,*</sup>, 
    <a href="https://marcofiorucci.github.io/" style="color: #000000 !important; text-decoration: none;">Marco Fiorucci</a><sup style="color: #000000 !important;">1,*</sup>, 
    <a href="https://www.math.unipd.it/~ballan/" style="color: #000000 !important; text-decoration: none;">Lamberto Ballan</a><sup style="color: #000000 !important;">1</sup>
  </div>

  <!-- Affiliazioni e nota -->
  <div style="font-size: 1rem; color: #111111 !important; opacity: 1 !important; line-height: 1.5;">
    <span style="color: #111111 !important; opacity: 1 !important;"><sup>1</sup> University of Padua &nbsp;&nbsp;&nbsp; <sup>2</sup> Harbin Institute of Technology</span><br>
    <small style="color: #333333 !important; opacity: 1 !important;"><sup>*</sup> Equal contribution</small>
  </div>

  <!-- Conference -->
  <div style="font-size: 1.1rem; font-weight: bold; color: #000000 !important; margin-top: 1rem;">
    NeurIPS 2026
  </div>
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
eof
git add _projects/rankalign.md
git commit -m "Fix inline styling for authors and affiliations to force high contrast"
git push origin main

EOFù
