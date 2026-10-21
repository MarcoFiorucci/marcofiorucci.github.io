---
layout: page
permalink: /rankalign/
title: RankAlign
description: Vision-Language Representation Alignment via Rank Transformation
nav: false
---

abstract: >
  While the Platonic Representation Hypothesis posits that vision and language models converge toward compatible latent geometries, recovering class-level correspondences between unpaired modalities without cross-modal supervision remains challenging. Existing relational matching methods compare within-modality similarity kernels directly, although the same semantic structure may be represented through different numerical parameterizations across modalities. We propose RankAlign, a rank-based normalization strategy for class-level unpaired vision-language matching. RankAlign transforms each within-modality similarity kernel into an ordinal relational representation before permutation matching, while leaving the correspondence space and matching solver unchanged. The resulting representation is invariant to strictly increasing reparameterizations of similarity values while preserving the ordinal structure used for matching. We provide exact-recovery and stability guarantees that characterize correspondence recovery under both exact and partial ordinal agreement. Experiments across diverse frozen vision and language encoders and multiple datasets demonstrate improved and more stable class-level correspondence recovery, including under label corruption and domain shift.
---

<!-- CSS ad alto contrasto per forzare la visibilità del testo nero -->
<style>
  body, p, span, h1, h2, h3, h4, h5, h6, li, table, th, td {
    color: #000000 !important;
  }
  .page-content, .post, .container {
    color: #000000 !important;
  }
</style>

<div class="clearfix" style="color: #000000 !important;">

  <!-- Autori e Affiliazioni -->
  <div class="author-list" style="color: #000000 !important; font-size: 1.15rem; margin-top: 0.5rem; margin-bottom: 0.5rem;">
    <span style="font-weight: 600;">Enzhe Zhao</span><sup>*</sup>, 
    <span style="font-weight: 600;">Marco Fiorucci</span><sup>*</sup>, 
    <span style="font-weight: 600;">Lamberto Ballan</span>
  </div>

  <div class="affiliations" style="color: #444444 !important; font-size: 0.95rem; margin-bottom: 1.5rem;">
    University of Padua, Italy
    <br>
    <small><sup>*</sup> Equal contribution</small>
  </div>

  <!-- Abstract -->
  <h2 style="color: #000000 !important; margin-top: 2rem;">Abstract</h2>
  <p style="color: #000000 !important; font-size: 1.1rem; line-height: 1.7; text-align: justify;">
    {{ page.abstract }}
  </p>

  <!-- Overview & Figura -->
  <h2 style="color: #000000 !important; margin-top: 2.5rem;">Overview</h2>
  <p style="color: #000000 !important; font-size: 1.05rem; line-height: 1.6;">
    Overview of the RankAlign architecture and representation alignment pipeline.
  </p>

  <div class="row justify-content-center mt-4 mb-3">
    <div class="col-sm-10 mt-3 mt-md-0 text-center">
      {% include figure.liquid path="assets/img/rankalign/pipeline.png" title="RankAlign Pipeline Overview" class="img-fluid rounded z-depth-1" %}
    </div>
  </div>
  <div class="caption" style="color: #000000 !important; text-align: center; font-size: 0.95rem; margin-bottom: 2rem;">
    <strong>Figure 1:</strong> RankAlign framework for Vision-Language Representation Alignment via Rank Transformation.
  </div>

  <!-- Resources -->
  <h2 style="color: #000000 !important; margin-top: 2.5rem;">Resources</h2>
  <p style="color: #000000 !important; font-size: 1.1rem;">
    [<a href="https://arxiv.org/" target="_blank" style="color: #0000EE !important; text-decoration: underline; font-weight: bold;">Paper (arXiv)</a>] &nbsp;&nbsp;
    [<a href="https://github.com/marcofiorucci" target="_blank" style="color: #0000EE !important; text-decoration: underline; font-weight: bold;">Code (GitHub)</a>]
  </p>

  <!-- BibTeX -->
  <h2 style="color: #000000 !important; margin-top: 2.5rem;">Citation</h2>
  <pre style="background-color: #f4f4f4; padding: 15px; border-radius: 5px; border: 1px solid #ddd; color: #000000 !important; font-size: 0.85rem;"><code>@inproceedings{zhao2026rankalign,
  title={RankAlign: Vision-Language Representation Alignment via Rank Transformation},
  author={Zhao, Enzhe and Fiorucci, Marco and Ballan, Lamberto},
  booktitle={Advances in Neural Information Processing Systems (NeurIPS)},
  year={2026}
}</code></pre>

</div>