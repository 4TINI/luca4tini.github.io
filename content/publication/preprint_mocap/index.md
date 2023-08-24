---
title: "Markerless 3D human pose tracking through multiple cameras and AI: Enabling high accuracy, robustness, and real-time performance"
authors:
- Luca Fortini
- Mattia Leonori
- Juan Manuel Gandarias
- Elena De Momi
- Arash Ajoudani
date: ""
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-01-03T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Tracking 3D human motion in real-time is crucial for numerous applications across many fields. Traditional approaches involve attaching artificial fiducial objects or sensors to the body, limiting their usability and comfort-of-use and consequently narrowing their application fields. Recent advances in Artificial Intelligence (AI) have allowed for markerless solutions. However, most of these methods operate in 2D, while those providing 3D solutions compromise accuracy and real-time performance. To address this challenge and unlock the potential of visual pose estimation methods in real-world scenarios, we propose a markerless framework that combines multi-camera views and 2D AI-based pose estimation methods to track 3D human motion. Our approach integrates a Weighted Least Square (WLS) algorithm that computes 3D human motion from multiple 2D pose estimations provided by an AI-driven method. The method is integrated within the Open-VICO framework allowing simulation and real-world execution. Several experiments have been conducted, which have shown high accuracy and real-time performance, demonstrating the high level of readiness for real-world applications and the potential to revolutionize human motion capture. 

# Summary. An optional shortened abstract.
summary: We propose a markerless framework that combines multi-camera views and 2D AI-based pose estimation methods to track 3D human motion. Our approach integrates a Weighted Least Square (WLS) algorithm that computes 3D human motion from multiple 2D pose estimations provided by an AI-driven method.

tags:
- ROS
- mocap
featured: true

links:
url_pdf: https://arxiv.org/abs/2303.18119
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
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---
<!-- 
{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
