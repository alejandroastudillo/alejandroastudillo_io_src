---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Speed-Up of Nonlinear Model Predictive Control for Robot Manipulators Using Task and Data Parallelism"
authors:
  - admin
  - Joris Gillis
  - Goele Pipeleers
  - Wilm Decré
  - Jan Swevers
date: 2022-03-11T10:37:38+02:00
doi: "10.1109/AMC51637.2022.9729271"

# Schedule page publish date (NOT publication's date).
publishDate: 2022-09-15T10:37:38+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "2022 IEEE 17th International Conference on Advanced Motion Control (AMC)"
publication_short: "IEEE AMC 2022"

abstract: "The repetitive evaluation of computationally expensive functions in the objective and constraints represents
a bottleneck in the solution of the underlying optimal control problem (OCP) of nonlinear model predictive controllers (MPC) for robot manipulators. We address this problem by exploiting the parallel evaluation of such functions within the execution of a first-order and a second-order OCP solution algorithm, such as the proximal averaged Newton-type method for optimal control (PANOC) and the sequential convex quadratic programming (SCQP) method, respectively. The use of task parallelism with multicore executions and data parallelism with single-instruction-multiple-data (SIMD) instructions is shown to effectively reduce the solution time of the underlying OCP so that the satisfaction of real-time constraints in the deployment of MPC for robot manipulators can be achieved."

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

url_pdf: "https://lirias.kuleuven.be/retrieve/640748"
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
