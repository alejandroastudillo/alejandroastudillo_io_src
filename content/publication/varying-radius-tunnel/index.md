---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Varying-Radius Tunnel-Following NMPC for Robot Manipulators Using Sequential Convex Quadratic Programming"
authors:
  - admin
  - Goele Pipeleers
  - Joris Gillis
  - Wilm Decré
  - Jan Swevers
date: 2022-10-03T19:21:46+02:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-09-14T19:21:46+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Modeling, Estimation and Control Conference 2022"
publication_short: "MECC 2022"

abstract: "The tunnel-following nonlinear model predictive control (NMPC) scheme for robot manipulators allows the definition of tasks where deviations from a given path reference are allowed but upper-bounded by a user-defined parameter, which for a position tunnel represents the radius of the tunnel. The underlying optimal control problem (OCP) in this scheme can be efficiently solved by using the sequential convex quadratic programming (SCQP) method. Up to now, this scheme has been implemented with constant tunnel radii, although several tasks, such as human-robot collaboration or pick-and-place tasks, would benefit from variable radii throughout task execution. The SCQP method is however not able to exploit the structure of varying-radius tunnel constraints, which can lead to unstable iterations of the SQP method. In this work, we propose a reformulation of the tunnel constraints to overcome this issue, allowing the use of the SCQP method to efficiently solve the underlying OCP. We also provide insight into an efficient implementation of the SCQP method using the lin operator and prove the main theorem underlying such operator. Simulation results of a pick-and-place task involving a varying-radius tunnel are presented to support the applicability of the proposed methods."

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

url_pdf: "https://kuleuven.limo.libis.be/discovery/fulldisplay?docid=lirias3769060&context=SearchWebhook&vid=32KUL_KUL:Lirias&search_scope=lirias_profile&tab=LIRIAS&adaptor=SearchWebhook&lang=en"
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
