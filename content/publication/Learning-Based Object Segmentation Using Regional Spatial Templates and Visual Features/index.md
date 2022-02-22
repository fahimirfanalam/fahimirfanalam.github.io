---
title: "Learning-Based Object Segmentation Using Regional Spatial Templates and Visual Features"
authors:
    - Iker Gondra
    - admin

date: "2012-09-22"
doi: "10.1007/978-3-642-33564-8_48"

# Schedule page publish date (NOT publication's date).
publishDate: "2012-09-22"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: International Conference on Computer Vision and Graphics
publication_short: In *Springer*

abstract: Semantically accurate segmentation of an object of interest (OOI) is a critical step in computer vision tasks. In order to bridge the gap between low-level visual features and high-level semantics, a more complete model of the OOI is needed. To this end, we revise the concept of directional spatial templates and introduce regional directional spatial templates as a means of including spatial relationships among OOI regions into the model. We present an object segmentation algorithm that learns a model which includes both visual and spatial information. Given a training set of images containing the OOI, each image is oversegmented into visually homogeneous regions. Next, Multiple Instance Learning identifies regions that are likely to be part of the OOI. For each pair of such regions and for each relationship, a regional template is formed. The computational cost of template generation is reduced by sampling the reference region with a pixel set that is descriptive of its shape. Experiments indicate that regional templates are an effective way of including spatial information into the model which in turn results in a very significant improvement in segmentation performance.

# Summary. An optional shortened abstract.
summary: Semantically accurate segmentation of an object of interest (OOI) is a critical step in computer vision tasks. In order to bridge the gap between low-level visual features and high-level semantics, a more complete model of the OOI is needed. To this end, we revise the concept of directional spatial templates and introduce regional directional spatial templates as a means of including spatial relationships among OOI regions into the model. We present an object segmentation algorithm that learns a model which includes both visual and spatial information. Given a training set of images containing the OOI, each image is oversegmented into visually homogeneous regions. Next, Multiple Instance Learning identifies regions that are likely to be part of the OOI. For each pair of such regions and for each relationship, a regional template is formed. The computational cost of template generation is reduced by sampling the reference region with a pixel set that is descriptive of its shape. Experiments indicate that regional templates are an effective way of including spatial information into the model which in turn results in a very significant improvement in segmentation performance.

tags:
    - Springer

featured: false

# links:
#     - name: Custom Link
#       url: http://example.org
url_source: "https://link.springer.com/chapter/10.1007%2F978-3-642-33564-8_48"
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
