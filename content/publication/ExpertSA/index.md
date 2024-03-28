---
title: "Medical image fusion based on convolutional neural networks and non-subsampled contourlet transform"
authors:
- Zeyu Wang
- Xiongfei Li
- Haoran Duan
- Yanchi Su
- Xiaoli Zhang
- Xinjiang Guan
date: "2021-01-08T00:00:00Z"
doi: "https://doi.org/10.1016/j.eswa.2021.114574"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-03-28T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: "Expert Systems with Applications"
publication_short: ""

abstract: Although many powerful convolutional neural networks (CNN) have been applied to various image processing fields, due to the lack of datasets for network training and the significant different intensities of diverse multi-modal source images at the same location, CNN cannot be directly used for the field of medical image fusion (MIF), which is a major problem and limits the development of this field. In this article, a novel multimodal medical image fusion method based on non-subsampled contourlet transform (NSCT) and CNN is presented. The proposed algorithm not only solves this problem, but also exploits the advantages of both NSCT and CNN to obtain better fusion results. In the proposed algorithm, source multi-modality images are decomposed into low and high frequency subbands. For high frequency subbands, a new perceptual high frequency CNN (PHF-CNN), which is trained in the frequency domain, is designed as an adaptive fusion rule. In the matter of the low frequency subband, two result maps are adopted to generate the decision map. Finally, fused frequency subbands are integrated by the inverse NSCT. To verify the effectiveness of the proposed algorithm, ten state-of-the-art MIF algorithms are selected as comparative algorithms. Subjective evaluations by five doctors as well as objective evaluations by seven image quality metrics, demonstrate that the proposed algorithm is superior to the other comparative algorithms in terms of fusing multimodal medical images.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

links:
url_pdf: 'https://www.sciencedirect.com/science/article/pii/S0957417421000154'
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
@article{WANG2021114574,
title = {Medical image fusion based on convolutional neural networks and non-subsampled contourlet transform},
journal = {Expert Systems with Applications},
volume = {171},
pages = {114574},
year = {2021},
issn = {0957-4174},
doi = {https://doi.org/10.1016/j.eswa.2021.114574},
url = {https://www.sciencedirect.com/science/article/pii/S0957417421000154},
author = {Zeyu Wang and Xiongfei Li and Haoran Duan and Yanchi Su and Xiaoli Zhang and Xinjiang Guan},
keywords = {Medical image fusion, Convolutional neural network, Non-subsampled contourlet transform},
}
```


<!-- Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
