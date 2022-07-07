---
title: "DeMis: Data-efficient Misinformation Detection using Reinforcement Learning"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Lisa Singh

date: "2022-07-07T00:00:00Z"
doi: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the European Conference on Machine Learning and Principles and Practice of Knowledge Discovery in Databases (ECML-PKDD)*
publication_short: In ***ECML-PKDD***

abstract: Given the speed and spread of information on social media, the influence and impact of misinformation can be consequential. Deep learning approaches are state-of-the-art for many natural language processing tasks, including misinformation detection. To train deep learning algorithms effectively, a large amount of training data is essential. Unfortunately, while unlabeled data are abundant, manually-labeled data are lacking for misinformation detection. In this paper, we propose DeMis, a novel reinforcement learning (RL) framework to detect misinformation on Twitter in a resource-constrained environment, i.e. limited labeled data. The main novelties result from (1) using reinforcement learning to identify high-quality weak labels to use with manually-labeled data to jointly train a classifier, and (2) using fact-checked claims to construct weak labels from unlabeled tweets. We empirically show the strength of this approach over the current state of the art and demonstrate its effectiveness in a low-resourced environment, outperforming other models by up to 8% (F1 score. We also find that our method is more robust to heavily imbalanced data. Finally, to support reproducibility, we publish a package containing code, trained models, and labeled data sets.

# Summary. An optional shortened abstract.
summary: We propose a novel reinforcement learning framework for misinformation detection on Twitter. We release both code, data and pre-trained models.

tags: [misinformation, data-efficient, misinformation-detection, NLP, reinforcement-learning, twitter, computational-social-science]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: PDF
  url: https://drive.google.com/file/d/1oQL5R5YiaO3Wdj6o7Nqd7BVAN2kSMxN8/view?usp=sharing

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
