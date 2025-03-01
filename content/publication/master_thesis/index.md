---
title: "Tracing and profiling machine learning dataflow applications on GPU"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2018-09-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2018-09-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["7"]

# Publication name and optional abbreviated publication name.
# publication: In *Wowchemy Conference*
# publication_short: In *ICW*

abstract: Recently, increasing computing capabilities have been required in various areas like scientific computing, video games and graphical rendering or artificial intelligence. These domains usually involve the processing of a large amount of data, intended to be performed as fast as possible. Unfortunately, hardware improvements have recently slowed down. The CPU clock speed, for example, is not increasing much any more, possibly nearing technological limits. Physical constraints like the heat dissipation or fine etching are the main reasons for that. Consequently, new opportunities like parallel processing using heterogeneous architectures became popular. In this context, the traditional processors get support from other computing units like graphical processors. In order to program these, the dataflow model offers several advantages. It is inherently parallel and thus well adapted. In this context, guaranteeing optimal performances is another main concern. For that, tracing and profiling central processing and graphical processing units are two useful techniques that can be considered. Several tools exist, like LTTng and FTrace that can trace the operating system and focus on the central processor. In addition, proprietary tools offered by hardware vendors can help to analyze and monitor the graphical processor. However, these tools are specific to one type of hardware and lack flexibility. Moreover, none of them target in particular dataflow applications executed on a heterogeneous platform.



# Summary. An optional shortened abstract.
summary: <b style="font-size:120%;color:#008080">Master Thesis</b></b><br> Develop tracing and profiling tools for dataflow machine learning applications with GPU acceleration.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: Polypublie
  url: https://publications.polymtl.ca/3242/

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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
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
