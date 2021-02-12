---
title: "Wang, C., Kang, S., et al. Edge Detection of Cryptic Lamellipodia Assisted by Deep Learning, bioRxiv."

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

date: "2017-08-21T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-08-21T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *bioRxiv*
# publication_short: In *ICW*

abstract: Cell protrusion plays important roles in cell migration by pushing plasma membrane forward. Cryptic lamellipodia induce the protrusion of submarginal cells in collective cell migration where cells are attached and move together. Although computational image analysis of cell protrusion has been done extensively, the study on protrusion activities of cryptic lamellipodia is limited due to difficulties in image segmentation. This study seeks to aid in the computational analysis of submarginal cell protrusion in collective cell migration by using deep learning to detect the cryptic lamellipodial edges from fluorescence time-lapse movies. Due to the noisy features within overlapping cells, the conventional image analysis algorithms such as Canny edge detector and intensity thresholding are limited. By combining Canny edge detector, Convolutional Neural Networks (CNNs), and local intensity thresholding, we were able to detect cryptic lamellipodial edges of submarginal cells with high accuracy from the fluorescence time-lapse movies of PtK1 cells stained with a plasma membrane marker. We used relatively small effort to prepare the training set to train the CNN to detect the cryptical lamellipodial edges in fluorescence time-lapse movies. This work demonstrates that deep learning can be combined with the conventional image analysis algorithms to facilitate the computational analysis of highly complex time-lapse movies of collective cell migration.

# Summary. An optional shortened abstract.
summary: By combining Canny edge detector, Convolutional Neural Networks (CNNs), and local intensity thresholding, we were able to detect cryptic lamellipodial edges of submarginal cells with high accuracy from the fluorescence time-lapse movies.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.biorxiv.org/content/10.1101/181263v1.full'
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
