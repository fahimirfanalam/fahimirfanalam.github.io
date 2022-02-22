---
title: "Combining Unmixing and Deep Feature Learning for Hyperspectral Image Classification"
authors:
    - admin
    - Jun Zhou
    - Lei Tong
    - Alan Wee-Chung Liew
    - Yongsheng Gao

date: "2017-12-21"
doi: "10.1109/DICTA.2017.8227419"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-12-21"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "2017 International Conference on Digital Image Computing: Techniques and Applications (DICTA)"
publication_short: In *IEEE*

abstract: Image classification is one of the critical tasks in hyperspectral remote sensing. In recent years, significant improvement have been achieved by various classification methods. However, mixed spectral responses from different ground materials still create confusions in complex scenes. In this regard, unmixing approaches are being successfully carried out to decompose mixed pixels into a collection of spectral signatures. Considering the usefulness of these techniques, we propose to utilize the unmixing results as an input to classifiers for better classification accuracy. We propose a novel band group based structure preserving nonnegative matrix factorization (NMF) method to estimate the individual spectral responses from different materials within different ranges of wavelengths. Then we train a convolutional neural network (CNN) with the unmixing results to generate powerful features and eventually classify the data. This method is evaluated on a new dataset and compared with several state-of-the-art models, which shows the promising potential of our method.

# Summary. An optional shortened abstract.
summary: Image classification is one of the critical tasks in hyperspectral remote sensing. In recent years, significant improvement have been achieved by various classification methods. However, mixed spectral responses from different ground materials still create confusions in complex scenes. In this regard, unmixing approaches are being successfully carried out to decompose mixed pixels into a collection of spectral signatures. Considering the usefulness of these techniques, we propose to utilize the unmixing results as an input to classifiers for better classification accuracy. We propose a novel band group based structure preserving nonnegative matrix factorization (NMF) method to estimate the individual spectral responses from different materials within different ranges of wavelengths. Then we train a convolutional neural network (CNN) with the unmixing results to generate powerful features and eventually classify the data. This method is evaluated on a new dataset and compared with several state-of-the-art models, which shows the promising potential of our method.

tags:
    - IEEE

featured: false

# links:
#     - name: Custom Link
#       url: http://example.org
url_source: "https://ieeexplore.ieee.org/document/8227419"
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
