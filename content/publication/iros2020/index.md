---
title: "A framework for real-time and personalisable human ergonomics monitoring"
authors:
- Luca Fortini
- Marta Lorenzini
- Wansoo Kim
- Elena De Momi
- Arash Ajoudani
author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2020-10-24T00:00:00Z"
doi: "10.1109/IROS45743.2020.9341560"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-01-03T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "2020 IEEE/RSJ International Conference on Intelligent Robots and Systems"
publication_short: "IROS"

abstract: The objective of this paper is to present a personalisable human ergonomics framework that integrates a method for real-time identification of a human model and an ergonomics monitoring function. The human model is based on a floating base structure and on a Statically Equivalent Serial Chain (SESC) model used for the estimation of the whole-body centre of Mass (CoM). A recursive linear regression algorithm (i.e., Kalman filter) is developed to achieve the online identification of the SESC parameters. A visual feedback provides a minimum set of suggested human poses to speed up the identification process, while enhancing the model accuracy based on a convergence value. The online ergonomics monitoring function computes and displays the overloading effects on body joints in heavy lifting tasks. The overloading joint torques are calculated based on the displacement of the Center of Pressure (CoP) between the measured one and the estimated one. Unlike our previous work, the entire process, from the model identification (personalisation) to ergonomics monitoring, is performed in real-time. We evaluated the efficacy of the proposed method through human experiments during model identification and load lifting tasks. Results demonstrate the high exploitation potential of the framework in industrial settings, due to its fast personalisation and ergonomics monitoring capacity.

# Summary. An optional shortened abstract.
summary:  The objective of this paper is to present a personalisable human ergonomics framework that integrates a method for real-time identification of a human model and an ergonomics monitoring function. 

tags:
- Ergonomics
- HRI
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=4y5FAIUGLUI'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: [SOPHIA, Ergo-Lean]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
