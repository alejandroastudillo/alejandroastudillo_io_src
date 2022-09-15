---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Mixed Use of Analytical Derivatives and Algorithmic Differentiation for NMPC of Robot Manipulators"
authors:
  - admin
  - Justin Carpentier
  - Joris Gillis
  - Goele Pipeleers
  - Jan Swevers
date: "2021-10-24T00:00:00Z"
doi: "10.1016/j.ifacol.2021.11.156"

# Schedule page publish date (NOT publication's date).
publishDate: 2022-09-12T08:40:52+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Modeling, Estimation and Control Conference 2021"
publication_short: "MECC 2021"

abstract: "In the context of nonlinear model predictive control (NMPC) for robot manipulators, we address the problem of enabling the mixed and transparent use of algorithmic differentiation (AD) and efficient analytical derivatives of rigid-body dynamics (RBD) to decrease the solution time of the subjacent optimal control problem (OCP). Efficient functions for RBD and their analytical derivatives are made available to the numerical optimization framework CasADi by overloading the operators in the implementations made by the RBD library Pinocchio and adding a derivative-overloading feature to CasADi. A comparison between analytical derivatives and AD is made based on their influence on the solution time of the OCP, showing the benefits of using analytical derivatives for RBD in optimal control of robot manipulators."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "https://lirias.kuleuven.be/retrieve/648392"
url_code: "https://github.com/alejandroastudillo/urdf2modelcasadi"
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
