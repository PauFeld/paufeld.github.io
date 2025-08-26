---
title: 'Vesselvae: Recursive variational autoencoders for 3d blood vessel synthesis'
authors:
- Paula Feldman
- Miguel Fainstein
- Viviana Siless
- Claudio Delrieux
- Emmanuel Iarussi
date: '2023-01-01'
publishDate: '2025-08-01T19:00:01.583652Z'
publication_types:
- paper-conference
publication: '*International Conference on Medical Image Computing and Computer-Assisted
  Intervention*'

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: We present a data-driven generative framework for synthesizing blood vessel 3D geometry. This is a challenging task due to the complexity of vascular systems, which are highly variating in shape, size, and structure. Existing model-based methods provide some degree of control and variation in the structures produced, but fail to capture the diversity of actual anatomical data. We developed VesselVAE, a recursive variational Neural Network that fully exploits the hierarchical organization of the vessel and learns a low-dimensional manifold encoding branch connectivity along with geometry features describing the target surface. After training, the VesselVAE latent space can be sampled to generate new vessel geometries. To the best of our knowledge, this work is the first to utilize this technique for synthesizing blood vessels. We achieve similarities of synthetic and real data for radius (.97), length (.95), and tortuosity (.96). By leveraging the power of deep neural networks, we generate 3D models of blood vessels that are both accurate and diverse, which is crucial for medical and surgical training, hemodynamic simulations, and many other purposes.

# Summary. An optional shortened abstract.
summary: We present a data-driven recursive method to generate 3D vascular structures

tags:
- Generative Modelling
- Vasculature

featured: true

links:
- name: Custom Link
  url: https://link.springer.com/chapter/10.1007/978-3-031-43907-0_7
url_pdf: http://arxiv.org/pdf/1512.04133v1
url_code: 'https://github.com/LIA-DiTella/VesselVAE'


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 
  filename: "static/uploads/vessel_thumbnail.jpg"
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
