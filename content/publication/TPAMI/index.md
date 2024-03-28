---
title: "Dynamic Unary Convolution in Transformers"
authors:
- Haoran Duan
- Yang Long
- Shidong Wang
- Haofeng Zhang
- Chris G Willcocks
- Ling Shao
date: "2023-11-01T00:00:00Z"
doi: "10.1109/TPAMI.2022.3233482"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-03-28T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Pattern Analysis and Machine Intelligence"
publication_short: "TPAMI"

abstract: It is uncertain whether the power of transformer architectures can complement existing convolutional neural networks. A few recent attempts have combined convolution with transformer design through a range of structures in series, where the main contribution of this paper is to explore a parallel design approach. While previous transformed-based approaches need to segment the image into patch-wise tokens, we observe that the multi-head self-attention conducted on convolutional features is mainly sensitive to global correlations and that the performance degrades when these correlations are not exhibited. We propose two parallel modules along with multi-head self-attention to enhance the transformer. For local information, a dynamic local enhancement module leverages convolution to dynamically and explicitly enhance positive local patches and suppress the response to less informative ones. For mid-level structure, a novel unary co-occurrence excitation module utilizes convolution to actively search the local co-occurrence between patches. The parallel-designed Dynamic Unary Convolution in Transformer (DUCT) blocks are aggregated into a deep architecture, which is comprehensively evaluated across essential computer vision tasks in image-based classification, segmentation, retrieval and density estimation. Both qualitative and quantitative results show our parallel convolutional-transformer approach with dynamic and unary convolution outperforms existing series-designed structures.

# Summary. An optional shortened abstract.
summary: Hybrid Transformer with help of convolution operations for various tasks.

tags:
- Source Themes
featured: true

links:
url_pdf: 'https://ieeexplore.ieee.org/abstract/document/10004645'
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
