---
title: "Identifying High Quality Training Data for Misinformation Detection"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Jaren Haber
- admin
- Lisa Singh
- Alexander Chen
- Adrian Pizzo
- Anna Pogrebivsky
- Joyce Yang

date: "2023-04-30T00:00:00Z"
doi: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the International Conference on Data Science, Technology and Applications (DATA)*
publication_short: In ***DATA***

abstract: Misinformation spread through social media poses a grave threat to public health, interfering with the best scientific evidence available. This spread was particularly visible during the COVID-19 pandemic. To track and curb misinformation, an essential first step is to detect it. One component of misinformation detection is finding examples of misinformation posts that can serve as training data for misinformation detection algorithms. In this paper, we focus on the challenge of collecting high-quality training data in misinformation detection applications. To that end, we demonstrate the effectiveness of a simple methodology and show its viability on five myths related to COVID-19. Our methodology incorporates both dictionary-based sampling and predictions from weak learners to identify a reasonable number of myth examples for data labeling. To aid researchers in adjusting this methodology for specific use cases, we use word usage entropy to describe when fewer iterations of samplin g and training will be needed to obtain high-quality samples. Finally, we present a case study that shows the prevalence of three of our myths on Twitter at the beginning of the pandemic.

# Summary. An optional shortened abstract.
summary: This paper presents an analysis of different methods for collecting training data in order to train a machine learning classifier for misinformation detection.

tags: [NLP, misinformation]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: Conference Paper
  url: https://doi.org/10.5220/0012089000003541

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

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
