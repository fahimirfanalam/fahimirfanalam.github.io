---
title: "Abundance-Guided Superpixels and Recurrent Neural Network for Hyperspectral Image Classification"
authors:
    - admin
    - Jun Zhou
    - Alan Wee-Chung Liew

date: "2020-01-02"
# doi: "10.1109/DICTA47822.2019.8946060"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-01-02"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "2019 Digital Image Computing: Techniques and Applications (DICTA)"
publication_short: "*2019 Digital Image Computing: Techniques and Applications (DICTA)*"

abstract: Mixed spectral responses from different ground materials often create confusions in complex remote sensing scenes and restrict classification performance. In this regard, unmixing approaches are being successfully carried out to decompose mixed pixels into a collection of spectral signatures. In this paper, we propose a method to integrate unmixing into a deep feature learning model in order to classify hyperspectral data. We propose to generate superpixels from the abundance estimations of the underlying materials of the image obtained from an unsupervised endmember extraction algorithm called vertex component analysis (VCA). The mean abundances of the superpixels are then used as features for a deep classifier. Our proposed deep model, formulated as a joint convolutional neural network and recurrent neural network, receives significant spectral-spatial information in the data to produce better and powerful features and achieve improved classification performance than several alternative methods.

# Summary. An optional shortened abstract.
summary: Mixed spectral responses from different ground materials often create confusions in complex remote sensing scenes and restrict classification performance. In this regard, unmixing approaches are being successfully carried out to decompose mixed pixels into a collection of spectral signatures. In this paper, we propose a method to integrate unmixing into a deep feature learning model in order to classify hyperspectral data. We propose to generate superpixels from the abundance estimations of the underlying materials of the image obtained from an unsupervised endmember extraction algorithm called vertex component analysis (VCA). The mean abundances of the superpixels are then used as features for a deep classifier. Our proposed deep model, formulated as a joint convolutional neural network and recurrent neural network, receives significant spectral-spatial information in the data to produce better and powerful features and achieve improved classification performance than several alternative methods.

tags:
    - Vertex Component Analysis
    - CNN
    - Remote Sensing
    - Hyperspectral Image

featured: false

# links:
#     - name: Custom Link
#       url: http://example.org
url_source: "https://ieeexplore.ieee.org/document/8946060"
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

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
