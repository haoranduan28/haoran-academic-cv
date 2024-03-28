---
title: "MRL-Seg: Overcoming Imbalance in Medical Image Segmentation with Multi-Step Reinforcement Learning"
authors:
- Feiyang Yang
- Xiongfei Li
- Haoran Duan 
- Feilong Xu
- Yawen Huang
- Xiaoli Zhang
- Yang Long
- Yefeng Zheng
date: "2023-11-T00:00:00Z"
doi: "10.1109/JBHI.2023.3336726"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-03-28T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Journal of Biomedical and Health Informatics"
publication_short: "JBHI"

abstract: Medical image segmentation is a critical task for clinical diagnosis and research. However, dealing with highly imbalanced data remains a significant challenge in this domain, where the region of interest (ROI) may exhibit substantial variations across different slices. This presents a significant hurdle to medical image segmentation, as conventional segmentation methods may either overlook the minority class or overly emphasize the majority class, ultimately leading to a decrease in the overall generalization ability of the segmentation results. To overcome this, we propose a novel approach based on multi-step reinforcement learning, which integrates prior knowledge of medical images and pixel-wise segmentation difficulty into the reward function. Our method treats each pixel as an individual agent, utilizing diverse actions to evaluate its relevance for segmentation. To validate the effectiveness of our approach, we conduct experiments on four imbalanced medical datasets, and the results show that our approach surpasses other state-of-the-art methods in highly imbalanced scenarios. These findings hold substantial implications for clinical diagnosis and research.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

links:
url_pdf: 'https://ieeexplore.ieee.org/abstract/document/10336383'
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
@ARTICLE{10336383,
  author={Yang, Feiyang and Li, Xiongfei and Duan, Haoran and Xu, Feilong and Huang, Yawen and Zhang, Xiaoli and Long, Yang and Zheng, Yefeng},
  journal={IEEE Journal of Biomedical and Health Informatics}, 
  title={MRL-Seg: Overcoming Imbalance in Medical Image Segmentation With Multi-Step Reinforcement Learning}, 
  year={2024},
  volume={28},
  number={2},
  pages={858-869},
  keywords={Image segmentation;Transformers;Reinforcement learning;Lesions;Medical diagnostic imaging;Task analysis;Training;Deep learning;imbalanced medical image segmentation;radiomics;reinforcement learning},
  doi={10.1109/JBHI.2023.3336726}}
```


<!-- Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
