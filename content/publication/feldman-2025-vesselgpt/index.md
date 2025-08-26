---
title: 'VesselGPT: Autoregressive Modeling of Vascular Geometry'
authors:
- Paula Feldman
- Martin Sinnona
- Claudio Delrieux
- Viviana Siless
- Emmanuel Iarussi
date: '2025-09-25'
publishDate: '2025-08-01T19:00:01.599107Z'
publication_types:
- paper-conference
publication: '*International Conference on Medical Image Computing and Computer-Assisted
  Intervention*'


# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract:  Anatomical trees are critical for clinical diagnosis and treatment planning, yet their complex and diverse geometry make accurate representation a significant challenge. Motivated by the latest advances in large language models, we introduce an autoregressive method for synthesizing anatomical trees. Our approach first embeds vessel structures into a learned discrete vocabulary using a VQ-VAE architecture, then models their generation autoregressively with a GPT-2 model. This method effectively captures intricate geometries and branching patterns, enabling realistic vascular tree synthesis. Comprehensive qualitative and quantitative evaluations reveal that our technique achieves high-fidelity tree reconstruction with compact discrete representations. Moreover, our B-spline representation of vessel cross-sections preserves critical morphological details that are often overlooked in previous’ methods parameterizations. To the best of our knowledge, this work is the first to generate blood vessels in an autoregressive manner.

# Summary. An optional shortened abstract.
summary: We present an autoregressive method to generate 3D vascular structures

tags:
- Generative Modelling
- Vasculature

featured: true

links:
- name: Custom Link
  url: https://arxiv.org/pdf/2505.13318
url_pdf: https://arxiv.org/pdf/2505.13318
url_code: 'https://github.com/LIA-DiTella/VesselGPT-MICCAI'


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 
  filename: "static/uploads/vesselgpt.jpg"
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
