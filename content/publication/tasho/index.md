---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Tasho: A Python Toolbox for Rapid Prototyping and Deployment of Optimal Control Problem-Based Complex Robot Motion Skills "
authors:
  - Ajay Sathya
  - admin
  - Joris Gillis
  - Wilm Decré
  - Goele Pipeleers
  - Jan Swevers

# Author notes (optional)
author_notes:
  - "Equal contribution"
  - "Equal contribution"

date: 2022-12-26T19:28:31+02:00
doi: "10.1109/IROS47612.2022.9981681"

# Schedule page publish date (NOT publication's date).
publishDate: 2022-09-14T19:28:31+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "2022 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS 2022)"
publication_short: "IEEE IROS 2022"

abstract: "We present Tasho (Task specification for receding horizon control), an open-source Python toolbox that facilitates systematic programming of optimal control problem (OCP)-based robot motion skills. Separation-of-concerns is followed while designing the components of a motion skill, which promotes their modularity and reusability. This allows us to program complex motion tasks by configuring and composing simpler tasks. We provide templates for several basic tasks like point-to-point and end-effector path-following tasks to speed up prototyping. Internally, the task’s symbolic expressions are computed using CasADi and the resulting OCP is transcribed using Rockit. A wide and growing range of mature open-source optimization solvers are supported for solving the OCP. Monitor functions can be easily specified and are automatically deployed with the motion skill, so that the generated motion skills can be easily embedded in a larger control architecture involving higher-level discrete controllers. The motion skills thus programmed can be directly deployed on robot platforms using the C-code generation capabilities of CasADi. The toolbox has been validated through several experiments both in simulation and on physical robot systems. The open-source toolbox can be accessed at: https://gitlab.kuleuven.be/meco-software/tasho"

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

url_pdf: "https://kuleuven.limo.libis.be/discovery/fulldisplay?docid=lirias3778595&context=SearchWebhook&vid=32KUL_KUL:Lirias&search_scope=lirias_profile&tab=LIRIAS&adaptor=SearchWebhook&lang=en"
url_code: "https://gitlab.kuleuven.be/meco-software/tasho"
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
