---
title: "EfficientTDNN: Efficient Architecture Search for Speaker Recognition"
authors:
- Zhen Hong Rui Wang
- Zhihua Wei
- Haoran Duan
- Yang Long
- Shouling Ji
date: "2022-06-17T00:00:00Z"
doi: "10.1109/TASLP.2022.3182856"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-03-28T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: "IEEE/ACM Transactions on Audio, Speech, and Language Processing"
publication_short: ""

abstract: Convolutional neural networks (CNNs), such as the time-delay neural network (TDNN), have shown their remarkable capability in learning speaker embedding. However, they meanwhile bring a huge computational cost in storage size, processing, and memory. Discovering the specialized CNN that meets a specific constraint requires a substantial effort of human experts. Compared with hand-designed approaches, neural architecture search (NAS) appears as a practical technique in automating the manual architecture design process and has attracted increasing interest in spoken language processing tasks such as speaker recognition. In this paper, we propose EfficientTDNN, an efficient architecture search framework consisting of a TDNN-based supernet and a TDNN-NAS algorithm. The proposed supernet introduces temporal convolution of different ranges of the receptive field and feature aggregation of various resolutions from different layers to TDNN. On top of it, the TDNN-NAS algorithm quickly searches for the desired TDNN architecture via weight-sharing subnets, which surprisingly reduces computation while handling the vast number of devices with various resources requirements. Experimental results on the VoxCeleb dataset show the proposed EfficientTDNN enables approximate 1013 architectures concerning depth, kernel, and width. Considering different computation constraints, it achieves a 2.20% equal error rate (EER) with 204 M multiply-accumulate operations (MACs), 1.41% EER with 571 M MACs as well as 0.94% EER with 1.45 G MACs. Comprehensive investigations suggest that the trained supernet generalizes subnets not sampled during training and obtains a favorable trade-off between accuracy and efficiency.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

links:
url_pdf: 'https://ieeexplore.ieee.org/abstract/document/9798861'
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
@ARTICLE{9798861,
  author={Wang, Rui and Wei, Zhihua and Duan, Haoran and Ji, Shouling and Long, Yang and Hong, Zhen},
  journal={IEEE/ACM Transactions on Audio, Speech, and Language Processing}, 
  title={EfficientTDNN: Efficient Architecture Search for Speaker Recognition}, 
  year={2022},
  volume={30},
  number={},
  pages={2267-2279},
  keywords={Computer architecture;Speaker recognition;Training;Neural networks;Microprocessors;Kernel;Convolution;Efficient search;neural architecture search;progressive learning;speaker recognition;time-delay neural network},
  doi={10.1109/TASLP.2022.3182856}}
```


<!-- Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
