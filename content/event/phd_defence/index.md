---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Fast model predictive control for robotic manipulators: efficient computations and operations"
event:
event_url:
location: "Ph.D. Public Defence"
address:
  street: "Kasteelpark Arenberg 41"
  city: "Leuven"
  region:
  postcode: "3001"
  country: "Belgium"
summary:
abstract: "The implementation of robotic applications is currently facing various control challenges that simple controllers fail to address, e.g., systems are increasingly complex, need to comply with constraints and need to account for several, sometimes conflicting performance objectives. Model predictive control (MPC) is an advanced control technique that explicitly accounts for all these challenges by considering system models and solving constrained optimization problems in real-time at every control step. However, wide adoption of MPC in complex robotic applications is impeded by two issues. First, low-level drivers in robotic systems require input updates at high frequency, typically in the order of 1 kHz, which is a control frequency that is difficult to meet for MPC due to its inherent computational complexity. Second, MPC development and deployment is not straightforward and comes with a high engineering cost because proper tools are missing. This work addresses both issues, reducing the computational complexity of MPC implementations for robotic applications and reducing the engineering time required for its deployment. It covers (i) the use of efficient formulations of robot dynamics and their analytical derivatives, (ii) the mixed and transparent use of such analytical derivatives and algorithmic differentiation within an optimization framework, (iii) the efficient evaluation of computationally expensive functions in nonlinear programs by means of task- and data-level parallelization, and (iv) the efficient implementation of numerical optimization algorithms that accelerate the solution of the underlying optimal control problem. Moreover, it consolidates these advances within an easy-to-use, open-source framework that defines a direct workflow from problem definition to robot-based solution deployment. These developments help bridge the gap between advanced optimization-based controllers, like MPC, and complex robotic applications."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2023-05-15T17:00:00+02:00
date_end: 2023-05-15T19:00:00+02:00
all_day: false

# Schedule page publish date (NOT event date).
publishDate: 2023-04-17T09:05:46+02:00

authors: []
tags: []

# Is this a featured event? (true/false)
featured: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

# Optional filename of your slides within your event's folder or a URL.
url_slides:

url_code:
url_pdf:
url_video:

# Markdown Slides (optional).
#   Associate this event with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
