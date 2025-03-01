---
title: 'LogoRA: Local-Global Representation Alignment for Robust Time Series Classification'
authors:
- Huanyu Zhang
- Yi-Fan Zhang
- Zhang Zhang
- Qingsong Wen
- Liang Wang
date: '2024-01-01'
publishDate: '2025-03-01T09:39:32.674856Z'
publication_types:
- article-journal
publication: '*IEEE Transactions on Knowledge and Data Engineering*'

abstract: Unsupervised domain adaptation (UDA) of time series aims to teach models to identify consistent patterns across various temporal scenarios, disregarding domain-specific differences, which can maintain their predictive accuracy and effectively adapt to new domains. However, existing UDA methods struggle to adequately extract and align both global and local features in time series data. To address this issue, we propose the Local-Global Representation Alignment framework (LogoRA), which employs a two-branch encoder–comprising a multi-scale convolutional branch and a patching transformer branch. The encoder enables the extraction of both local and global representations from time series. A fusion module is then introduced to integrate these representations, enhancing domain-invariant feature alignment from multi-scale perspectives. To achieve effective alignment, LogoRA employs strategies like invariant feature learning on the source domain, utilizing triplet loss for fine alignment and dynamic time warping-based feature alignment. Additionally, it reduces source-target domain gaps through adversarial training and per-class prototype alignment. Our evaluations on four time-series datasets demonstrate that LogoRA outperforms strong baselines by up to 12.52%, showcasing its superiority in time series UDA tasks.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Time Series Classification
- Domain Adaptation
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/abstract/document/10679601
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'We propose the Local-Global Representation Alignment framework (LogoRA), which combines multi-scale convolutional and transformer encoders, integrates representations with a fusion module, and employs advanced alignment strategies, achieving state-of-the-art performance on four time-series datasets.'
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
slides: ''
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).

---
