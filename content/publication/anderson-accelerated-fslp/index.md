---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Anderson Accelerated Feasible Sequential Linear Programming"
authors: 
  - David Kiessling
  - Pieter Pas
  - admin
  - Panagiotis Patrinos
  - Jan Swevers
date: 2022-12-16T15:41:42+01:00
doi: "10.48550/arXiv.2212.02718"

# Schedule page publish date (NOT publication's date).
publishDate: 2023-03-03T18:04:03+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Accepted to IFAC World Congress 2023"
publication_short: ""

abstract: "This paper proposes an accelerated version of Feasible Sequential Linear Programming (FSLP): the AA(d)-FSLP algorithm. FSLP preserves feasibility in all intermediate iterates by means of an iterative update strategy which is based on repeated evaluation of zero-order information. This technique was successfully applied to techniques such as Model Predictive Control and Moving Horizon Estimation, but it can exhibit slow convergence. Moreover, keeping all iterates feasible in FSLP entails a large number of additional constraint evaluations. In this paper, Anderson Acceleration (AA(d)) is applied to the zero-order update strategy improving the convergence rate and therefore decreasing the number of constraint evaluations in the inner iterative procedure of the FSLP algorithm. AA(d) achieves an improved contraction rate in the inner iterations, with proven local linear convergence. In addition, it is observed that due to the improved zero-order update strategy, AA(d)-FSLP takes larger steps to find an optimal solution, yielding faster overall convergence. The performance of AA(d)-FSLP is examined for a time-optimal point-to-point motion problem of a parallel SCARA robot. The reduction of the number of constraint evaluations and overall iterations compared to FSLP is successfully demonstrated."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "https://arxiv.org/abs/2212.02718"
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
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
slides: ""
---
