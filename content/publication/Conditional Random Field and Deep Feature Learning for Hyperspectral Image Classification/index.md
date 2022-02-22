---
title: "Conditional Random Field and Deep Feature Learning for Hyperspectral Image Classification"
authors:
    - admin
    - Jun Zhou
    - Alan Wee-Chung Liew
    - Xiuping Jia
    - Jocelyn Chanussot
    - Yongsheng Gao

date: "2018-09-20"
doi: "10.1109/TGRS.2018.2867679"

# Schedule page publish date (NOT publication's date).
publishDate: "2018-09-20"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: IEEE Transactions on Geoscience and Remote Sensing 
publication_short: In *IEEE*

abstract: Image classification is considered to be one of the critical tasks in hyperspectral remote sensing image processing. Recently, a convolutional neural network (CNN) has established itself as a powerful model in classification by demonstrating excellent performances. The use of a graphical model such as a conditional random field (CRF) contributes further in capturing contextual information and thus improving the classification performance. In this paper, we propose a method to classify hyperspectral images by considering both spectral and spatial information via a combined framework consisting of CNN and CRF. We use multiple spectral band groups to learn deep features using CNN, and then formulate deep CRF with CNN-based unary and pairwise potential functions to effectively extract the semantic correlations between patches consisting of 3-D data cubes. Furthermore, we introduce a deep deconvolution network that improves the final classification performance. We also introduced a new data set and experimented our proposed method on it along with several widely adopted benchmark data sets to evaluate the effectiveness of our method. By comparing our results with those from several state-of-the-art models, we show the promising potential of our method.

# Summary. An optional shortened abstract.
summary: Image classification is considered to be one of the critical tasks in hyperspectral remote sensing image processing. Recently, a convolutional neural network (CNN) has established itself as a powerful model in classification by demonstrating excellent performances. The use of a graphical model such as a conditional random field (CRF) contributes further in capturing contextual information and thus improving the classification performance. In this paper, we propose a method to classify hyperspectral images by considering both spectral and spatial information via a combined framework consisting of CNN and CRF. We use multiple spectral band groups to learn deep features using CNN, and then formulate deep CRF with CNN-based unary and pairwise potential functions to effectively extract the semantic correlations between patches consisting of 3-D data cubes. Furthermore, we introduce a deep deconvolution network that improves the final classification performance. We also introduced a new data set and experimented our proposed method on it along with several widely adopted benchmark data sets to evaluate the effectiveness of our method. By comparing our results with those from several state-of-the-art models, we show the promising potential of our method.

tags:
    - IEEE

featured: false

# links:
#     - name: Custom Link
#       url: http://example.org
url_source: "https://ieeexplore.ieee.org/abstract/document/8469063"
# url_code: "#"
# url_dataset: "#"
# url_pdf: "#"
# url_poster: "#"
# url_project: "#"
# url_slides: "#"
# url_video: "#"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# # image:
#     caption: "Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)"
#     focal_point: ""
#     preview_only: false
# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#     - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
