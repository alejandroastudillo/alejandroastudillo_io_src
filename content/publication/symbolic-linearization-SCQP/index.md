---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Position and Orientation Tunnel-Following NMPC of Robot Manipulators Based on Symbolic Linearization in Sequential Convex Quadratic Programming"
authors:
  - admin
  - Joris Gillis
  - Moritz Diehl
  - Wilm Decré
  - Goele Pipeleers
  - Jan Swevers
date: 2022-01-13T09:11:17+02:00
doi: "10.1109/LRA.2022.3142396"

# Schedule page publish date (NOT publication's date).
publishDate: 2022-09-12T09:11:17+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Robotics and Automation Letters"
publication_short: "IEEE RA-L"

abstract: "The tunnel-following nonlinear model predictive control (NMPC) scheme allows to exploit acceptable deviations around a path reference. This is done by using convex-over-nonlinear functions as objective and constraints in the underlying optimal control problem (OCP). The convex-over-nonlinear structure is exploited by algorithms such as the generalized Gauss-Newton (GGN) method or the sequential convex quadratic programming (SCQP) method to reduce the computational complexity of the OCP solution. However, the modeling effort and engineering time required to implement these methods is high. We address the problem of reducing the modeling effort in the implementation of SCQP, focusing on a standard sequential quadratic programming (SQP) implementation where symbolic linearization is applied to the nonlinear part of the convex-over-nonlinear functions in the objective and constraints. The novelty of this letter is twofold. It introduces a novel operator that applies symbolic linearization in a transparent and easy way to solve nonconvex OCPs with the SCQP method, and introduces a meaningful representation of an orientation-tunnel for robotic applications by means of a convex-over-nonlinear constraint, which preserves the convexity exploitation by the SCQP method. The proposed technique is demonstrated in a tunnel-following task for a 7-degrees-of-freedom manipulator."

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

url_pdf: "https://lirias.kuleuven.be/retrieve/651310"
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video: "https://youtu.be/I4Sqhr-PY6I"

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
