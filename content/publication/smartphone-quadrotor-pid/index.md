---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Altitude and attitude cascade controller for a smartphone-based quadcopter"
authors:
  - admin
  - Pedro Muñoz
  - Fredy Álvarez
  - Esteban Rosero
date: 2017-06-15T21:09:19+01:00
doi: "10.1109/ICUAS.2017.7991400"

# Schedule page publish date (NOT publication's date).
publishDate: 2017-07-27T21:09:19+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "In the 2017 International Conference on Unmanned Aircraft Systems (ICUAS)"
publication_short: "In the ICUAS 2017 Proceedings"

abstract: "This paper presents the design and implementation of Android-based cascade PID controller structures to control the altitude and attitude of a quadcopter, and the sensor fusion algorithms implemented to estimate its flight dynamics. The main goal of this research is to stabilize the attitude of an unmanned aerial vehicle (UAV), such as a quadcopter, and control its altitude using exclusively the sensors and processor of a smartphone on-board. As the sensors embedded in the smartphones are not accurate enough to measure the altitude of the quadcopter, a linear Kalman filter for relative altitude estimation was designed and implemented. Here, it is described precisely the hardware that was used to build the test platform, the non-linear an linearized quadcopter model, the software structure to execute the controllers in the smartphone, the sensor fusion algorithms implemented to obtain reliable data from the smartphone sensors, and the cascade PID controllers design. Finally, the success of the proposed system is evidenced in the results of a set of experimental tests. In these tests, the quadcopter attitude was regulated after some disturbances were applied to the system and its altitude was controlled after the reference was changed."

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

url_pdf: "https://ieeexplore.ieee.org/document/7991400"
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
