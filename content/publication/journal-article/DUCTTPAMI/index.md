---
title: "Dynamic Unary Convolution in Transformers"
authors:
- Haoran Duan
- Yang Long
- Shidong Wang
- Haofeng Zhang
- Chris G Willcocks
- Ling Shao

date: "2023-01-02T00:00:00Z"
doi: "10.1109/TPAMI.2022.3233482"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Pattern Analysis and Machine Intelligence "
publication_short: ""

abstract: It is uncertain whether the power of transformer architectures can complement existing convolutional neural networks. A few recent attempts have combined convolution with transformer design through a range of structures in series, where the main contribution of this paper is to explore a parallel design approach. While previous transformed-based approaches need to segment the image into patch-wise tokens, we observe that the multi-head self-attention conducted on convolutional features is mainly sensitive to global correlations and that the performance degrades when these correlations are not exhibited. We propose two parallel modules along with multi-head self-attention to enhance the transformer. For local information, a dynamic local enhancement module leverages convolution to dynamically and explicitly enhance positive local patches and suppress the response to less informative ones. For mid-level structure, a novel unary co-occurrence excitation module utilizes convolution to actively search the local co-occurrence between patches. The parallel-designed Dynamic Unary Convolution in Transformer (DUCT) blocks are aggregated into a deep architecture, which is comprehensively evaluated across essential computer vision tasks in image-based classification, segmentation, retrieval and density estimation. Both qualitative and quantitative results show our parallel convolutional-transformer approach with dynamic and unary convolution outperforms existing series-designed structures.

# Summary. An optional shortened abstract.
summary: Hybrid Transformer with convolution operations.

featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://durham-repository.worktribe.com/preview/1185357/37786.pdf
url_code: 
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
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
slides: example
---
title: "Wearable-based behaviour interpolation for semi-supervised human activity recognition"
authors:
- Haoran Duan
- Shidong Wang 
- Varun Ojha
- Shizheng Wang 
- Yawen Huang 
- Yang Long
- Rajiv Ranjan
- Yefeng Zheng

date: "2024-04-02T00:00:00Z"
doi: "10.1016/j.ins.2024.120393"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Information Sciences "
publication_short: ""

abstract: While traditional feature engineering for Human Activity Recognition (HAR) involves a trial-and-error process, deep learning has emerged as a preferred method for high-level representations of sensor-based human activities. However, most deep learning-based HAR requires a large amount of labelled data and extracting HAR features from unlabelled data for effective deep learning training remains challenging. We, therefore, introduce a deep semi-supervised HAR approach, MixHAR, which concurrently uses labelled and unlabelled activities. Our MixHAR employs a linear interpolation mechanism to blend labelled and unlabelled activities while addressing both inter- and intra-activity variability. A unique challenge identified is the activity-intrusion problem during mixing, for which we propose a mixing calibration mechanism to mitigate it in the feature embedding space. Additionally, we rigorously explored and evaluated the five conventional/popular deep semi-supervised technologies on HAR, acting as the benchmark of deep semi-supervised HAR. Our results demonstrate that MixHAR significantly improves performance, underscoring the potential of deep semi-supervised techniques in HAR.

# Summary. An optional shortened abstract.
summary: Attention for semi-supervised human activity recognition

featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://www.sciencedirect.com/science/article/pii/S0020025524003062
url_code: 
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
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
slides: example
---
