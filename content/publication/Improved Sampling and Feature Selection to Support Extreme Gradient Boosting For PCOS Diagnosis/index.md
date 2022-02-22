---
title: "Improved Sampling and Feature Selection to Support Extreme Gradient Boosting For PCOS Diagnosis"
authors:
    - Muhammad Sakib Khan Inan
    - Rubaiath E Ulfath
    - admin
    - Fateha Khanam Bappee
    - Rizwan Hasan

date: "2021-03-17"
doi: "10.1109/CCWC51732.2021.9375994"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-03-17"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: 2021 IEEE 11th Annual Computing and Communication Workshop and Conference (CCWC)
publication_short: In *IEEE*

abstract: PolyCystic Ovary Syndrome (PCOS) is one of the most common causes of female infertility, affecting a large number of women of reproductive age, even continuing far beyond the childbearing years. This hormonal disorder may further lead to the risk of other long-term complications. Considering the powerful recognition abilities of the probabilistic nature of ensemble-based gradient boosting algorithms, particularly in the field of the medical domain, we propose the use of Extreme Gradient Boosting, XGBoost, for early detection of PCOS. To strongly support an effective classification performance, we have resampled our data using a combination of SMOTE(Synthetic Minority Oversampling Techniques) & ENN (Edited Nearest Neighbour), to solve class imbalance and data outliers issues. Also, by exploiting popular statistical correlation methods, ANOVA Test Chi-Square Test, we have identified 23 most significant metabolic and clinical parameters that best classify PCOS conditions. Finally, we experimented with our model on a benchmark dataset collected from Kaggle to justify the effectiveness of our proposed findings where the Extreme Gradient Boosting classifier outperformed all other classifiers with a 10 Fold Cross-validation score of 96.03 % all over, along with a 98% Recall in the detection of patients not having PCOS, which outperforms all the existing recent methods where the numerical data-driven diagnosis of PCOS have been studied on this particular dataset.

# Summary. An optional shortened abstract.
summary: PolyCystic Ovary Syndrome (PCOS) is one of the most common causes of female infertility, affecting a large number of women of reproductive age, even continuing far beyond the childbearing years. This hormonal disorder may further lead to the risk of other long-term complications. Considering the powerful recognition abilities of the probabilistic nature of ensemble-based gradient boosting algorithms, particularly in the field of the medical domain, we propose the use of Extreme Gradient Boosting, XGBoost, for early detection of PCOS. To strongly support an effective classification performance, we have resampled our data using a combination of SMOTE(Synthetic Minority Oversampling Techniques) & ENN (Edited Nearest Neighbour), to solve class imbalance and data outliers issues. Also, by exploiting popular statistical correlation methods, ANOVA Test Chi-Square Test, we have identified 23 most significant metabolic and clinical parameters that best classify PCOS conditions. Finally, we experimented with our model on a benchmark dataset collected from Kaggle to justify the effectiveness of our proposed findings where the Extreme Gradient Boosting classifier outperformed all other classifiers with a 10 Fold Cross-validation score of 96.03 % all over, along with a 98% Recall in the detection of patients not having PCOS, which outperforms all the existing recent methods where the numerical data-driven diagnosis of PCOS have been studied on this particular dataset.

tags:
    - IEEE

featured: false

# links:
#     - name: Custom Link
#       url: http://example.org
url_source: "https://ieeexplore.ieee.org/document/9375994"
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
