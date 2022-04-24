---
title: "Classifying Ego-Vehicle Road Maneuvers from Dashcam Video"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- "Thomas F. Larsen"


# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2022-04-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["7"]

# Publication name and optional abbreviated publication name.
publication: 
publication_short: 

abstract: We propose a novel method to improve the calibration of neural networks under distribution shift. This method involves including an expected calibration error (ECE) term in the loss function in addition to a normal cross entropy term. We implement and evaluate this method on a variety of distribution shifts using the MNIST and CIFAR datasets as our training sets. We create a custom scale to measure the intensity of different shifts with intensities ranging from $1-10$. We give an example of such a shift on MNIST in Figure $\ref{mnist_contrast}$. The proposed solution significantly outperforms a baseline model trained without explicit uncertainty quantification. We evaluate these models on each shift and each intensity. On CIFAR-10, our method achieves an overall average of $.065$ test ECE, significantly outperforming the baseline model, which achieves $.234$ ECE. 

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
 - name: Slides (PPT)
   url: ""

url_pdf: 'undergraduate_thesis.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
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
# slides: example
---
