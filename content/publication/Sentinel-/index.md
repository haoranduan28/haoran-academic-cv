---
title: "Sentinel-Guided Zero-Shot Learning: A Collaborative Paradigm without Real Data Exposure"
authors:
- Fan Wan
- Xingyu Miao
- Haoran Duan
- Jingjing Deng
- Rui Gao
- Yang Long
date: "2024-03-14T00:00:00Z"
doi: "https://arxiv.org/html/2403.09363v1"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-03-28T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Circuits and Systems for Video Technology"
publication_short: ""

abstract: With increasing concerns over data privacy and model copyrights, especially in the context of collaborations between AI service providers and data owners, an innovative SG-ZSL paradigm is proposed in this work. SG-ZSL is designed to foster efficient collaboration without the need to exchange models or sensitive data. It consists of a teacher model, a student model and a generator that links both model entities. The teacher model serves as a sentinel on behalf of the data owner, replacing real data, to guide the student model at the AI service provider's end during training. Considering the disparity of knowledge space between the teacher and student, we introduce two variants of the teacher model the omniscient and the quasi-omniscient teachers. Under these teachers' guidance, the student model seeks to match the teacher model's performance and explores domains that the teacher has not covered. To trade off between privacy and performance, we further introduce two distinct security-level training protocols： white-box and black-box, enhancing the paradigm's adaptability. Despite the inherent challenges of real data absence in the SG-ZSL paradigm, it consistently outperforms in ZSL and GZSL tasks, notably in the white-box protocol. Our comprehensive evaluation further attests to its robustness and efficiency across various setups, including stringent black-box training protocol.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

links:
url_pdf: http://arxiv.org/pdf/1512.04133v1
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
@misc{wan2024sentinelguided,
      title={Sentinel-Guided Zero-Shot Learning: A Collaborative Paradigm without Real Data Exposure}, 
      author={Fan Wan and Xingyu Miao and Haoran Duan and Jingjing Deng and Rui Gao and Yang Long},
      year={2024},
      eprint={2403.09363},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```


<!-- Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
