---
title: "Attention-Driven Metapath Encoding in Heterogeneous Graphs"
authors:
- admin
date: "2024-12-30T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-12-30T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "One of the emerging techniques in node classification in heterogeneous graphs is to restrict message aggregation to pre-defined, semantically meaningful structures called metapaths. This work is the first attempt to incorporate attention into the process of encoding entire metapaths without dropping intermediate nodes. In particular, we construct two encoders: the first uses sequential attention to extend the multi-hop message passing algorithm designed in Wang et al. to the metapath setting, and the second incorporates direct attention to extract semantic relations in the metapath. The model then employs the intra-metapath and inter-metapath aggregation mechanisms of Wang et al. We furthermore use the powerful training scheduler specialized for heterogeneous graphs that was developed in Wong et al., ensuring the model slowly learns how to classify the most difficult nodes. The result is a resilient, general-purpose framework for capturing semantic structures in heterogeneous graphs. In particular, we demonstrate that our model is competitive with state-of-the-art models on performing node classification on the IMDB dataset, a popular benchmark introduced in Lv et al."
tags:
- Graph Neural Networks

featured: true

links:
url_pdf: https://arxiv.org/pdf/2412.20678
#url_code: ''
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: 'https://drive.google.com/file/d/1vfT2KnRS87nKL369RCfXmG_TdoF5UKcK/view?usp=sharing'
#url_source: '#'
#url_video: 'https://drive.google.com/file/d/1d8g3yNQ-GY2n66Y11SO4B7eQEKzLqx4W/view?usp=drive_link'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
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

In this paper, I propose and implement a novel heterogeneous graph neural network architecture for CPSC483 at Yale. The model implements an original attention-based mechanism to extract features from semantically meaningful relations (“metapaths”) inside a graph. I derive key results and conduct extensive testing of the model, documenting it in the detailed report.