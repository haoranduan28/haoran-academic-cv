---
title: "Dynamic visual-guided selection for zero-shot learning"
authors:
- Fan Wan
- Xingyu Miao
- Haoran Duan
- Jingjing Deng
- Rui Gao
- Yang Long
date: "2023-09-13T00:00:00Z"
doi: "https://doi.org/10.1007/s11227-023-05625-1"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-03-28T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: "The Journal of Supercomputing"
publication_short: ""

abstract: Zero-shot learning (ZSL) methods currently employed to identify seen or unseen classes rely on semantic attribute prototypes or class information. However, hand-annotated attributes are only for the category rather than for each image belonging to that category. Furthermore, attribute information is inconsistent across different images of the same category due to variant views. Therefore, we propose a dynamic visual-guided selection (DVGS) which helps dynamically focus on different regions and refines class prototype on each image. Instead of directly aligning an image’s global feature with its semantic class vector or its local features with all attribute vectors, the proposed method learns a vision-guided soft mask to refine the class prototype for each image. Additionally, it discovers the most task-relevant regions for fine-grained recognition with the refined class prototype. Extensive experiments on three benchmarks verify the effectiveness of our DVGS and achieve the new state-of-the-art. Our DVGS achieved the best results on fine-grained datasets within both the conventional zero-shot learning (CZSL) and generalized zero-shot learning (GZSL) settings. In particular, on the SUN dataset, our DVGS demonstrates a significant superiority of 10.2% in the CZSL setting compared with the second-best approach. Similarly, our method outperforms the second-best method by an average of 4% on CUB in both the CZSL and GZSL settings. Despite securing the second-best result on the AWA2 dataset, DVGS remains closely competitive, trailing the best performance by a mere 3.4% in CZSL and 1.2% in GZSL.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

links:
url_pdf: 'https://link.springer.com/article/10.1007/s11227-023-05625-1'
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
@article{654dc98f939a5f4082c1b402,	author={Yuan Zhou and Lei Xiang and Fan Liu and Haoran Duan and Yang Long},	pages={4401-4419},	title={Dynamic visual-guided selection for zero-shot learning},	volume=80,	year=2023,}
```


<!-- Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
