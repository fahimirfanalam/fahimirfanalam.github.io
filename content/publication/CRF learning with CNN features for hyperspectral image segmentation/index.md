---
title: "CRF learning with CNN features for hyperspectral image segmentation"
authors:
    - admin
    - Jun Zhou
    - Alan Wee-Chung Liew
    - Xiuping Jia

date: "2016-11-03"
# doi: "10.1109/IGARSS.2016.7730798"

# Schedule page publish date (NOT publication's date).
publishDate: "2016-11-03"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: 2016 IEEE International Geoscience and Remote Sensing Symposium (IGARSS)
publication_short: "*2016 IEEE International Geoscience and Remote Sensing Symposium (IGARSS)*"

abstract: This paper proposes a method that uses both spectral and spatial information to segment remote sensing hyperspectral images. After a hyperspectral image is over-segmented into superpixels, a deep Convolutional Neural Network (CNN) is used to perform superpixel-level labelling. To further delineate objects from a hyperspectral scene, this paper attempts to combine the properties of CNN and Conditional Random Field (CRF). A mean-field approximation algorithm for CRF inference is used and formulated with Gaussian pairwise potentials as Recurrent Neural Network. This combined network is then plugged into the CNN which leads to a deep network that has robust characteristics of both CNN and CRF. Preliminary results suggest the usefulness of this framework to a promising extent.

# Summary. An optional shortened abstract.
summary: This paper proposes a method that uses both spectral and spatial information to segment remote sensing hyperspectral images. After a hyperspectral image is over-segmented into superpixels, a deep Convolutional Neural Network (CNN) is used to perform superpixel-level labelling. To further delineate objects from a hyperspectral scene, this paper attempts to combine the properties of CNN and Conditional Random Field (CRF). A mean-field approximation algorithm for CRF inference is used and formulated with Gaussian pairwise potentials as Recurrent Neural Network. This combined network is then plugged into the CNN which leads to a deep network that has robust characteristics of both CNN and CRF. Preliminary results suggest the usefulness of this framework to a promising extent.

tags:
    - CNN
    - Superpixels
    - Hyperspectral Image
    - CRF
    - RNN
    - Remote Sensing

featured: false

# links:
#     - name: Custom Link
#       url: http://example.org
url_source: "https://ieeexplore.ieee.org/document/7730798"
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
