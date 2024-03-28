---
title: "A Self-supervised Residual Feature Learning Model for Multi-focus Image Fusion"
authors:
- Zeyu Wang
- Xiongfei Li
- Haoran Duan
- Xiaoli Zhang
date: "2022-06-23T00:00:00Z"
doi: "10.1109/TIP.2022.3184250"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-03-28T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Image Processing"
publication_short: "TIP"

abstract: Multi-focus image fusion (MFIF) attempts to achieve an “all-focused” image from multiple source images with the same scene but different focused objects. Given the lack of multi-focus image sets for network training, we propose a self-supervised residual feature learning model in this paper. The model consists of a feature extraction network and a fusion module. We select image super-resolution as a pretext task in the MFIF field, which is supported by a new residual gradient prior discovered by our theoretical study for low- and high-resolution (LR-HR) image pairs, as well as for multi-focus images. In the pretext task, our network’s training set is LR-HR image pairs generated from natural images, and HR images can be regarded as pseudo-labels of LR images. In the fusion task, the trained network extracts residual features of multi-focus images firstly. Secondly, the fusion module, consisting of an activity level measurement and a new boundary refinement method, is leveraged for the features to generated decision maps. Experimental results, both subjective evaluations and objective evaluations, demonstrate that our approach outperforms other state-of-the-art fusion algorithms.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: true

links:
url_pdf: 'https://ieeexplore.ieee.org/abstract/document/9805468'
# - name: Custom Link
#   url: http://example.org

# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

<!-- {{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}} -->
