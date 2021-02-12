---
title: "Wang, C., Zhang, X., et al. vU-net: accurate cell edge segmentation in time-lapse fluorescence live cell images based on convolutional neural network, bioRxiv."

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

date: "2017-09-21T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-09-21T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *bioRxiv*
# publication_short: In *ICW*

abstract: Time-lapse fluorescence live cell imaging has been widely used to study various dynamical processes in cell biology. However, fluorescence live cell images often have low contrast, noises, and uneven illumination, preventing accurate cell segmentation. The convolutional neural network has been successfully applied in natural image classification and segmentation by extracting hierarchical features, which could be transferred into other fields for image segmentation. Moreover, the temporal coherence in time-lapse images can allow us to extract sufficient features from a limited number of image frames to segment the entire time-lapse movies. In this paper, we propose a novel framework called vU-net, which integrates the VGG-161 pretrained model as an encoder and a U-net2 derived simplified convolutional structure to reconstruct cell edge with a higher accuracy using limited training images. We evaluated our framework on the high-resolution images of paxillin, a canonical adhesion marker in migrating PtK1 cells acquired by a Total Internal Reflection Fluorescence (TIRF) microscope, and achieved higher accuracy of cell segmentation than conventional U-net. We also validated our framework on noisy confocal fluorescence live images of GFP-mDia1 in PtK1 cells. We demonstrated that vU-net could be practically applied to challenging live cell movies since it required limited training sets and achieved highly accurate segmentation.

# Summary. An optional shortened abstract.
summary: We propose a novel framework called vU-net to reconstruct cell edge with a higher accuracy using limited training images.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.biorxiv.org/content/10.1101/191858v1.full'
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
