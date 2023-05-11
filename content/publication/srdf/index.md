---
title: "Multi-View Reconstruction using Signed Ray Distance Functions (SRDF)"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Yuanlu Xu
- Edmond Boyer
- Stefanie Wuhrer
- Tony Tung

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2023-04-25T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-04-25T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
# publication: In *Wowchemy Conference*
# publication_short: In *ICW*

abstract: In this paper, we address the problem of multi-view 3D shape reconstruction. While recent differentiable rendering approaches associated to implicit shape representations have provided breakthrough performance, they are still computationally heavy and often lack precision on the estimated geometries. To overcome these limitations we investigate a new computational approach that builds on a novel shape representation that is volumetric, as in recent differentiable rendering approaches, but parameterized with depth maps to better materialize the shape surface. The shape energy associated to this representation evaluates 3D geometry given color images and does not need appearance prediction but still benefits from volumetric integration when optimized. In practice we propose an implicit shape representation, the SRDF, based on signed distances which we parameterize by depths along camera rays. The associated shape energy considers the agreement between depth prediction consistency and photometric consistency, this at 3D locations within the volumetric representation. Various photo-consistency priors can be accounted for such as a median based baseline, or a more elaborated criterion as with a learned function. The approach retains pixel-accuracy with depth maps and is parallelizable. Our experiments over standard datasets shows that it provides state-of-the-art results with respect to recent approaches with implicit shape representations as well as with respect to traditional multi-view stereo methods.


# Summary. An optional shortened abstract.
summary: <b style="font-size:120%;color:#008080">CVPR 2023</b></b><br> Multi-View Reconstruction using Signed Ray Distance Functions (SRDF).
tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: ArXiv
  url: https://arxiv.org/pdf/2209.00082.pdf
- name: HAL
  url: https://hal.science/hal-03766943/

# url_pdf: ''
# url_code: ''
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Multi-View Reconstruction using Signed Ray Distance Functions (SRDF).'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
