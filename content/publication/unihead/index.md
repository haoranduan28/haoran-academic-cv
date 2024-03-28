---
title: "UniHead: Unifying Multi-Perception for Detection Heads"
authors:
- Hantao Zhou
- Rui Yang
- Yachao Zhang
- Haoran Duan
- Yawen Huang
- Runze Hu
- Xiu Li
- Yefeng Zheng
date: "2023-09-23T00:00:00Z"
doi: "https://arxiv.org/abs/2309.13242"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-03-28T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: The detection head constitutes a pivotal component within object detectors, tasked with executing both classification and localization functions. Regrettably, the commonly used parallel head often lacks omni perceptual capabilities, such as deformation perception, global perception and cross-task perception. Despite numerous methods attempt to enhance these abilities from a single aspect, achieving a comprehensive and unified solution remains a significant challenge. In response to this challenge, we have developed an innovative detection head, termed UniHead, to unify three perceptual abilities simultaneously. More precisely, our approach (1) introduces deformation perception, enabling the model to adaptively sample object features; (2) proposes a Dual-axial Aggregation Transformer (DAT) to adeptly model long-range dependencies, thereby achieving global perception; and (3) devises a Cross-task Interaction Transformer (CIT) that facilitates interaction between the classification and localization branches, thus aligning the two tasks. As a plug-and-play method, the proposed UniHead can be conveniently integrated with existing detectors. Extensive experiments on the COCO dataset demonstrate that our UniHead can bring significant improvements to many detectors. For instance, the UniHead can obtain +2.7 AP gains in RetinaNet, +2.9 AP gains in FreeAnchor, and +2.1 AP gains in GFL. The code will be publicly available.  Code Url：https://github.com/zht8506/UniHead

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

links:
url_pdf: 'https://arxiv.org/pdf/2309.13242.pdf'
# - name: Custom Link
#   url: http://example.org

url_code: 'https://github.com/zht8506/UniHead'
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
@misc{zhou2023unihead,
      title={UniHead: Unifying Multi-Perception for Detection Heads}, 
      author={Hantao Zhou and Rui Yang and Yachao Zhang and Haoran Duan and Yawen Huang and Runze Hu and Xiu Li and Yefeng Zheng},
      year={2023},
      eprint={2309.13242},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```


<!-- Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
