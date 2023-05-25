---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Advancing the Industrial Application of Model Predictive Control for Robot Manipulators: Improving Computational Efficiency and Facilitating Implementation"
authors: 
  - admin
date: 2023-05-15T17:00:00+02:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2023-05-25T14:40:14+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["7"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: "Ph.D. Thesis, KU Leuven"

abstract: "
The implementation of robotic applications encounters a number of challenges that simple controllers are unsuited to properly solve. For instance, robotic systems are becoming increasingly complex and applications must satisfy constraints inherent to the system or to the task itself, while taking into account several, sometimes conflicting, performance objectives. These challenges are explicitly taken into account by the advanced optimal control technique called model predictive control (MPC). In MPC, models are used to predict the system behavior within a defined prediction horizon, and at each control step a constrained optimization problem is solved in real time. However, wide adoption of MPC in complex robotic applications is impeded by two issues. First, low-level drivers in robotic systems require control input updates at high frequency, typically in the order of 1 kHz, which is a control frequency that is difficult to meet for MPC due to its inherent computational complexity. Second, MPC specification, prototyping and deployment is no easy task since appropriate tools that reduce the high engineering effort associated to it are not widely available. This work addresses both issues, reducing the computational complexity of MPC implementations for robotic applications and reducing the engineering time required for its specification, prototyping and deployment. It covers (i) the reduction of the computational complexity of general mathematical expressions, (ii) the use of efficient formulations of robot dynamics and their analytical derivatives, (iii) the mixed and transparent use of such analytical derivatives and algorithmic differentiation within an optimization framework, (iv) the efficient evaluation of computationally expensive functions in nonlinear programs by means of task- and data-level parallelization, and (v) the efficient implementation of numerical optimization algorithms that accelerate the solution of the underlying optimal control problem. Moreover, it consolidates these advances within an easy-to-use, open-source framework called Tasho, which defines a direct workflow from problem definition to robot-based solution deployment. These developments help bridge the gap between advanced optimization-based controllers, like MPC, and complex robotic applications."

# Summary. An optional shortened abstract.
summary: "The implementation of robotic applications is currently facing various control challenges that simple controllers fail to address, e.g., systems are increasingly complex, need to comply with constraints and need to account for several, sometimes conflicting performance objectives. Model predictive control (MPC) is an advanced control technique that explicitly accounts for all these challenges by considering system models and solving constrained optimization problems in real-time at every control step. However, wide adoption of MPC in complex robotic applications is impeded by its high computational and engineering complexity. This work addresses both issues, reducing the computational complexity of MPC implementations for robotic applications and reducing the engineering time required for its deployment. This research is supported by an MPC toolchain development in order to integrate all software in an open and modular fashion as to create a workflow from problem specification to deployment. The developments are validated computationally and experimentally on industrial robotic set-ups in the lab."

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

url_pdf: "https://kuleuven.limo.libis.be/discovery/fulldisplay?docid=lirias4079943&context=SearchWebhook&vid=32KUL_KUL:Lirias&search_scope=lirias_profile&tab=LIRIAS&adaptor=SearchWebhook&lang=en"
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
