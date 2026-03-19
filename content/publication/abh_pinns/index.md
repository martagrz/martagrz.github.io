---
title: "Solving Heterogeneous Agent Models with Physics-Informed Neural Networks"
authors:
- admin
date: "2025-08-08T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
#publication: "Uncovering Utility Functions from Observed Outcomes"
#publication_short: "Uncovering Utility Functions from Observed Outcomes"

abstract: Understanding household behaviour is essential for modelling macroeconomic dynamics and designing effective policy. While heterogeneous agent models offer a more realistic alternative to representative agent frameworks, their implementation poses significant computational challenges, particularly in continuous time. The Aiyagari-Bewley-Huggett (ABH) framework, recast as a system of partial differential equations, typically relies on grid-based solvers that suffer from the curse of dimensionality, high computational cost, and numerical inaccuracies. This paper introduces the ABH- PINN solver, an approach based on Physics-Informed Neural Networks (PINNs), which embeds the Hamilton-Jacobi-Bellman and Kolmogorov Forward equations directly into the neural network training objective. By replacing grid-based approximation with mesh-free, differentiable function learning, the ABH-PINN solver benefits from the advantages of PINNs of improved scalability, smoother solutions, and computational efficiency. Preliminary results show that the PINN-based approach is able to obtain economically valid results matching the established finite-difference solvers. We hope this will open new avenues for solving complex heterogeneous agent models in macroeconomics.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Computational Economics
- Physics-Informed Neural Networks
- Heterogeneous Agent Models 
featured: true

links:
#- name: Custom Link
#  url: http://example.org
#url_pdf: 'pdf/Grzeskiewicz_Solving_HAMs_with_PINNs.pdf'
#url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: ''
#url_source: '#'
#url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---
