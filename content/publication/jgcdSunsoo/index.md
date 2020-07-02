---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Extended H2 Filtering for Attitude Estimation in Low Power Microprocessors"
authors: [Sunsoo Kim, Vaishnav Tadiparthi, and Raktim Bhattacharya]
date: 2020-06-23T15:39:09-05:00
doi: ""

# Schedule page publish date (NOT publication's date).
#publishDate: 2020-07-02T15:39:09-05:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "Journal of Guidance, Control, and Dynamics"
publication_short: ""

abstract: "Accurate state estimation using low-cost MEMS (Micro Electro- Mechanical Systems) sensors present on Commercial-off-the-shelf (COTS) drones is a challenging problem. Most UAV systems use a combination of a gyroscope, an accelerometer, and a magnetometer to obtain measurements and estimate attitude.  Under this paradigm of sensor fusion, the Extended Kalman Filter (EKF) is the most popular algorithm for attitude estimation in UAVs. In this work, we propose a novel estimation technique called extended H2 filter that can overcome the limitations of the EKF, specifically with respect to computational speed, memory usage, and root mean squared error. We formulate our attitude-estimation algorithm using two distinct coordinate representations for the vehicle’s orientation: Euler angles and unit quaternions, each with its own sets of benefits and challenges. The H2 optimal filter gain is designed offline about a nominal operating point by solving a convex optimization problem, and the filter dynamics is implemented using the nonlinear system dynamics. This implementation of thisH2optimal estimator is referred as the extended H2 estimator. The proposed technique is tested on four cases corresponding to long time-scale motion, fast time-scale motion, transition from hover to forward flight for VTOL aircrafts, and an entire flight cycle (from take-off to landing).Its results are compared against that of the EKF in terms of the aforementioned performance metrics."

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

url_pdf: https://arxiv.org/pdf/2006.14385.pdf
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
