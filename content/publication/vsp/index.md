---
title: "VSP-Fuse: Multifocus Image Fusion Model Using the Knowledge Transferred From Visual Salience Priors"
authors:
- Zeyu Wang
- Xiongfei Li
- Shuang Yu
- Haoran Duan
- Xiaoli Zhang
- Jizheng Zhang
- Shiping Chen
date: "2022-12-15T00:00:00Z"
doi: "10.1109/TCSVT.2022.3229691"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-03-28T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Circuits and Systems for Video Technology"
publication_short: ""

abstract: Multifocus image fusion (MFIF), as an efficient way to improve the visual effect of images with partial focus defects, is of great significance in the field of image enhancement. According to the imaging principle of the lens, we summarize the visual salience priors (VSP) from the daily photo scene and two relationships from MFIF. Thereby, an edge-sensitive model for MFIF is presented in this study. Supported by VSP, we consider the correlation between salience object detection (SOD) and MFIF, and select the former as a pre-training task. SOD provides the network with realistic depth of field and bokeh effects to learn, and enhances the network’s ability to extract and express the edges of focused objects. Meanwhile, given the scarcity of real multifocus training sets, we propose a randomized approach to generate massive training sets and pseudo-labels based on limited unlabeled data. Besides, two attention modules are designed based on isometric domain transformation (IDT) in the traditional edge-preservation field. IDT removes interference information from feature maps in a low-cost manner, thereby facilitating channel-wise and spatial-wise weight assignments. Experimental results on four datasets show that the performance of our model is superior to that of many supervised models, without the need of any real MFIF training set.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

links:
url_pdf: 'https://ieeexplore.ieee.org/abstract/document/9989382'
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

**cite** 
```
@ARTICLE{9989382,
  author={Wang, Zeyu and Li, Xiongfei and Yu, Shuang and Duan, Haoran and Zhang, Xiaoli and Zhang, Jizheng and Chen, Shiping},
  journal={IEEE Transactions on Circuits and Systems for Video Technology}, 
  title={VSP-Fuse: Multifocus Image Fusion Model Using the Knowledge Transferred From Visual Salience Priors}, 
  year={2023},
  volume={33},
  number={6},
  pages={2627-2641},
  keywords={Training;Task analysis;Image edge detection;Visualization;Transforms;Feature extraction;Lenses;Multifocus image fusion;pre-training task;transfer learning;visual salience priors;attention},
  doi={10.1109/TCSVT.2022.3229691}}
```


<!-- Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
