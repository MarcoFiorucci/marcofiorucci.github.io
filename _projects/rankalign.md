---
layout: default
title: "RankAlign"
description: ""
img: 
importance: 1
category: work
---

<style>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap');

.post-header, .post-title, .post-description {
  display: none !important;
}

html, body, body.dark, html[data-theme="dark"] {
  background-color: #ffffff !important;
  color: #222222 !important;
}

div.publication-page {
  font-family: 'Inter', -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif !important;
  max-width: 900px !important;
  margin: 3rem auto !important;
  padding: 2rem !important;
  background-color: #ffffff !important;
  color: #222222 !important;
}

h1.publication-title {
  font-size: 2.3rem !important;
  font-weight: 700 !important;
  text-align: center !important;
  line-height: 1.25 !important;
  margin-bottom: 1.8rem !important;
  color: #111111 !important;
  letter-spacing: -0.02em;
}

div.publication-authors {
  text-align: center !important;
  font-size: 1.15rem !important;
  font-weight: 500 !important;
  margin-bottom: 0.3rem !important;
}

div.publication-authors .author-block {
  display: inline-block !important;
  margin: 0 8px !important;
}

div.publication-authors .author-block a {
  color: #0088cc !important;
  text-decoration: none !important;
}

div.publication-authors .author-block a:hover {
  text-decoration: underline !important;
}

/* Equal contribution leggero, senza grassetto e con il simbolo */
div.publication-equal-contrib {
  text-align: center !important;
  font-size: 0.95rem !important;
  color: #555555 !important;
  margin-bottom: 1rem !important;
  font-weight: 400 !important;
}

div.publication-affiliations {
  text-align: center !important;
  font-size: 1.05rem !important;
  color: #444444 !important;
  margin-bottom: 1rem !important;
  font-weight: 400 !important;
}

div.publication-affiliations .affiliation-block {
  display: inline-block !important;
  margin: 0 8px !important;
}

div.publication-venue {
  text-align: center !important;
  font-size: 1.15rem !important;
  color: #333333 !important;
  font-weight: 600 !important;
  margin-bottom: 2rem !important;
}

div.publication-links {
  display: flex !important;
  justify-content: center !important;
  gap: 12px !important;
  flex-wrap: wrap !important;
  margin-bottom: 2.5rem !important;
}

div.publication-links .link-block .button {
  display: inline-flex !important;
  align-items: center !important;
  gap: 8px !important;
  padding: 8px 18px !important;
  border-radius: 20px !important;
  background-color: rgba(0, 0, 0, 0.04) !important;
  border: 1px solid rgba(0, 0, 0, 0.15) !important;
  color: #333333 !important;
  font-size: 0.9rem !important;
  font-weight: 500 !important;
  text-decoration: none !important;
  transition: all 0.2s ease;
}

div.publication-links .link-block .button:hover {
  background-color: rgba(0, 0, 0, 0.08) !important;
  border-color: rgba(0, 0, 0, 0.3) !important;
}

div.publication-teaser {
  text-align: center !important;
  margin-bottom: 2.5rem !important;
  width: 100% !important;
}

div.publication-teaser img {
  width: 110% !important;
  max-width: 1050px !important;
  height: auto !important;
  border-radius: 8px !important;
  border: 1px solid rgba(0, 0, 0, 0.1) !important;
  display: block !important;
  margin-left: -5% !important;
}

div.publication-teaser figcaption {
  font-size: 0.9rem !important;
  color: #555555 !important;
  margin-top: 0.75rem !important;
  text-align: justify !important;
  padding: 0 10px !important;
}

h2.section-title {
  text-align: center !important;
  font-size: 1.5rem !important;
  font-weight: 600 !important;
  margin-top: 2.5rem !important;
  margin-bottom: 1rem !important;
  color: #111111 !important;
}

div.abstract-content {
  text-align: justify !important;
  font-size: 1.02rem !important;
  line-height: 1.7 !important;
  color: #333333 !important;
}

div.bibtex-box {
  background-color: rgba(0, 0, 0, 0.03) !important;
  border: 1px solid rgba(0, 0, 0, 0.1) !important;
  border-radius: 8px !important;
  padding: 16px 20px !important;
  margin-top: 1rem !important;
}

pre.bibtex-code {
  font-family: "SFMono-Regular", Consolas, "Liberation Mono", Menlo, monospace !important;
  font-size: 0.85rem !important;
  color: #a31515 !important;
  white-space: pre-wrap !important;
  word-break: break-word !important;
  margin: 0 !important;
  background: transparent !important;
}

hr.publication-divider {
  border: 0 !important;
  height: 1px !important;
  background: rgba(0, 0, 0, 0.1) !important;
  margin: 2.5rem 0 !important;
}
</style>

<div class="publication-page">

  <h1 class="publication-title">RankAlign: Vision-Language Representation Alignment via Rank Transformation</h1>

  <div class="publication-authors">
    <span class="author-block"><a href="#">Enzhe Zhao</a><sup>2,*</sup></span>
    <span class="author-block"><a href="#">Marco Fiorucci</a><sup>1,*</sup></span>
    <span class="author-block"><a href="#">Lamberto Ballan</a><sup>1</sup></span>
  </div>

  <div class="publication-equal-contrib">
    <span><sup>*</sup>equal contribution</span>
  </div>

  <div class="publication-affiliations">
    <span class="affiliation-block"><sup>1</sup> University of Padova</span>
    <span class="affiliation-block"><sup>2</sup> Harbin Institute of Technology</span>
  </div>

  <div class="publication-venue">
    NeurIPS 2026
  </div>

  <div class="publication-links">
    <span class="link-block">
      <a href="#" target="_blank" class="button">
        <i class="fa-solid fa-file-pdf"></i> Paper
      </a>
    </span>
    <span class="link-block">
      <a href="#" target="_blank" class="button">
        <i class="fa-solid fa-graduation-cap"></i> arXiv
      </a>
    </span>
    <span class="link-block">
      <a href="https://github.com/zez356/RankAlign" target="_blank" class="button">
        <i class="fa-brands fa-github"></i> Code
      </a>
    </span>
  </div>

  <div class="publication-teaser">
    <img src="{{ site.baseurl }}/assets/img/rankalign/pipeline.png" alt="Pipeline Overview">
    <figcaption>
      <strong>Figure 1: Pipeline Overview.</strong> The pipeline maps image and text embeddings into rank-based similarity kernels, followed by permutation matching for cross-modal alignment without paired data.
    </figcaption>
  </div>

  <hr class="publication-divider">

  <h2 class="section-title">Abstract</h2>
  <div class="abstract-content">
While the Platonic Representation Hypothesis posits that vision and language models converge toward compatible latent geometries, recovering class-level correspondences between unpaired modalities without cross-modal supervision remains challenging.
Existing relational matching methods compare within-modality similarity kernels directly, although the same semantic structure may be represented through different numerical parameterizations across modalities. We propose RankAlign, a rank-based normalization strategy for class-level unpaired vision-language matching. RankAlign transforms each within-modality similarity kernel into an ordinal relational representation before permutation matching, while leaving the correspondence space and matching solver unchanged. The resulting representation is invariant to strictly increasing reparameterizations of similarity values while preserving the ordinal structure used for matching. We provide exact-recovery and stability guarantees that characterize correspondence recovery under both exact and partial ordinal agreement. Experiments across diverse frozen vision and language encoders and multiple datasets demonstrate improved and more stable class-level correspondence recovery, including under label corruption and domain shift.
  </div>

  <hr class="publication-divider">

  <h2 class="section-title">Citation</h2>
  <div class="bibtex-box">
    <pre class="bibtex-code">@inproceedings{zhao2026rankalign,
  title={RankAlign: Vision-Language Representation Alignment via Rank Transformation},
  author={Zhao, Enzhe and Fiorucci, Marco and Ballan, Lamberto},
  booktitle={Advances in Neural Information Processing Systems (NeurIPS)},
  year={2026}
}</pre>
  </div>

</div>