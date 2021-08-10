---
title: "Wang, C., et al. Deep Learning-based Subcellular Phenotyping of Protrusion Dynamics Reveals Fine Differential Drug Responses at Subcellular and Single-Cell Levels, bioRxiv, 2022"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
# - Robert Ford

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2021-05-27T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-05-27T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *bioRxiv*
# publication_short: In *ICW*

abstract: Intracellular processes such as cytoskeletal organization and organelle dynamics exhibit massive subcellular heterogeneity. Although recent advances in fluorescence microscopy allow researchers to acquire an unprecedented amount of live cell image data at high spatiotemporal resolutions, the traditional ensemble-averaging of uncharacterized subcellular heterogeneity could mask important activities. Moreover, the curse of dimensionality of these complex dynamic datasets prevents access to critical mechanistic details of subcellular processes. Here, we establish an unsupervised machine learning framework called DeepHACKS (Deep phenotyping of Heterogeneous Activities in the Coordination of cytosKeleton at the Subcellular level) for “deep phenotyping,” which identifies rare subcellular phenotypes specifically sensitive to molecular perturbations. DeepHACKS dissects the heterogeneity of subcellular time-series datasets by allowing bi-directional LSTM (Long-Short Term Memory) neural networks to extract fine-grained temporal features by integrating autoencoders with conventional machine learning outcomes. We applied DeepHACKS to subcellular protrusion dynamics in pharmacologically perturbed epithelial cells, revealing fine differential responses of leading edge dynamics specific to each perturbation. Particularly, DeepHACKS in conjunction with blebistantin treatment revealed the emergence of rare subcellular and single-cell phenotypes driven by “bursting” protrusion. This suggests that the temporal features directly learned from leading edge dynamics enable fine-grained identification of drug-related phenotypes, which may not be accessible from static cell images. In summary, our study provides an analytical framework for detailed and quantitative understandings of molecular mechanisms hidden in their heterogeneity. DeepHACKS can be potentially applied to analyze various time-series data measured from other subcellular processes.

# Summary. An optional shortened abstract.
summary: We develop a deep learning-based framework "DeepHACKS" for subcellular phenotyping of protrusion dynamics to reveal fine differential drug responses at subcellular and single-Cell Levels.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.biorxiv.org/content/10.1101/2021.05.25.445699v1'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Chuangqi Wang**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.

# Fan commented the next two rows 2021-02-07
# projects:
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.

# Fan commented the next one row 2021-02-07
# slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
