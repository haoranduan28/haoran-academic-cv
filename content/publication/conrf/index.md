---
title: "ConRF: Zero-shot Stylization of 3D Scenes with Conditioned Radiation Fields"
authors:
- Xingyu Miao
- Yang Bai
- Haoran Duan
- Fan Wan
- Yawen Huang
- Yang Long
- Yefeng Zheng
date: "2024-02-02T00:00:00Z"
doi: "https://arxiv.org/html/2403.09363v1"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-03-28T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Most of the existing works on arbitrary 3D NeRF style transfer required retraining on each single style condition. This work aims to achieve zero-shot controlled stylization in 3D scenes utilizing text or visual input as conditioning factors. We introduce ConRF, a novel method of zero-shot stylization. Specifically, due to the ambiguity of CLIP features, we employ a conversion process that maps the CLIP feature space to the style space of a pre-trained VGG network and then refine the CLIP multi-modal knowledge into a style transfer neural radiation field. Additionally, we use a 3D volumetric representation to perform local style transfer. By combining these operations, ConRF offers the capability to utilize either text or images as references, resulting in the generation of sequences with novel views enhanced by global or local stylization. Our experiment demonstrates that ConRF outperforms other existing methods for 3D scene and single-text stylization in terms of visual quality.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

links:
url_pdf: 'https://arxiv.org/pdf/2402.01950.pdf'
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
@misc{miao2024conrf,
      title={ConRF: Zero-shot Stylization of 3D Scenes with Conditioned Radiation Fields}, 
      author={Xingyu Miao and Yang Bai and Haoran Duan and Fan Wan and Yawen Huang and Yang Long and Yefeng Zheng},
      year={2024},
      eprint={2402.01950},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```


<!-- Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
