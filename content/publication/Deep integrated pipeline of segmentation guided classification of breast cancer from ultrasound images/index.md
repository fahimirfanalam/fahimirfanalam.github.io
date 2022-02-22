---
title: "Deep integrated pipeline of segmentation guided classification of breast cancer from ultrasound images"
authors:
    - Muhammad Sakib Khan Inan
    - admin
    - Rizwan Hasan

date: "2022-02-17"
doi: "10.1016/j.bspc.2022.103553"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-02-17"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: Biomedical Signal Processing and Control, Elsevier
publication_short: In *Elsevier*

abstract: Breast cancer has become a symbol of tremendous concern in the modern world, as it is one of the major causes of cancer mortality worldwide. In this regard, breast ultrasonography images are frequently utilized by doctors to diagnose breast cancer at an early stage. However, the complex artifacts and heavily noised breast ultrasonography images make diagnosis a great challenge. Furthermore, the ever-increasing number of patients being screened for breast cancer necessitates the use of automated end-to-end technology for highly accurate diagnosis at a low cost and in a short time. In this concern, to develop an end-to-end integrated pipeline for breast ultrasonography image classification, we conducted an exhaustive analysis of image preprocessing methods such as K Means++ and SLIC, as well as four transfer learning models such as VGG16, VGG19, DenseNet121, and ResNet50. With a Dice-coefficient score of 63.4 in the segmentation stage and accuracy and an F1-Score (Benign) of 73.72 percent and 78.92 percent in the classification stage, the combination of SLIC, UNET, and VGG16 outperformed all other integrated combinations. Finally, we have proposed an end to end integrated automated pipelining framework which includes preprocessing with SLIC to capture super-pixel features from the complex artifact of ultrasonography images, complementing semantic segmentation with modified U-Net, leading to breast tumor classification using a transfer learning approach with a pre-trained VGG16 and a densely connected neural network. The proposed automated pipeline can be effectively implemented to assist medical practitioners in making more accurate and timely diagnoses of breast cancer.

# Summary. An optional shortened abstract.
summary: Breast cancer has become a symbol of tremendous concern in the modern world, as it is one of the major causes of cancer mortality worldwide. In this regard, breast ultrasonography images are frequently utilized by doctors to diagnose breast cancer at an early stage. However, the complex artifacts and heavily noised breast ultrasonography images make diagnosis a great challenge. Furthermore, the ever-increasing number of patients being screened for breast cancer necessitates the use of automated end-to-end technology for highly accurate diagnosis at a low cost and in a short time. In this concern, to develop an end-to-end integrated pipeline for breast ultrasonography image classification, we conducted an exhaustive analysis of image preprocessing methods such as K Means++ and SLIC, as well as four transfer learning models such as VGG16, VGG19, DenseNet121, and ResNet50. With a Dice-coefficient score of 63.4 in the segmentation stage and accuracy and an F1-Score (Benign) of 73.72 percent and 78.92 percent in the classification stage, the combination of SLIC, UNET, and VGG16 outperformed all other integrated combinations. Finally, we have proposed an end to end integrated automated pipelining framework which includes preprocessing with SLIC to capture super-pixel features from the complex artifact of ultrasonography images, complementing semantic segmentation with modified U-Net, leading to breast tumor classification using a transfer learning approach with a pre-trained VGG16 and a densely connected neural network. The proposed automated pipeline can be effectively implemented to assist medical practitioners in making more accurate and timely diagnoses of breast cancer.

tags:
    - Elsevier
    - Journal

featured: true

# links:
#     - name: Custom Link
#       url: http://example.org
url_source: "https://doi.org/10.1016/j.bspc.2022.103553"
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
