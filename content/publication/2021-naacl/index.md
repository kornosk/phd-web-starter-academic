---
title: "Knowledge Enhanced Masked Language Model for Stance Detection"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Lisa Singh

date: "2021-05-24T00:00:00Z"
doi: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 2021 Annual Conference of the North American Chapter of the Association for Computational Linguistics (NAACL)*
publication_short: In ***NAACL***

abstract: Detecting stance on Twitter is especially challenging because of the short length of each tweet, the continuous coinage of new terminology and hashtags, and the deviation of sentence structure from standard prose. Fine-tuned language models using large-scale in-domain data have been shown to be the new state-of-the-art for many NLP tasks, including stance detection. In this paper, we propose a novel BERT-based fine-tuning method that enhances the masked language model for stance detection. Instead of random token masking, we propose using a weighted log-odds-ratio to identify words with high stance distinguishability and then model an attention mechanism that focuses on these words. We show that our proposed approach outperforms the state of the art for stance detection on Twitter data about the 2020 US Presidential election.

# Summary. An optional shortened abstract.
summary: We propose a novel language modeling for stance detection. We release both data and pre-trained models.

tags: [stance-detection, NLP, language-modeling, BERT, twitter, politics, computational-social-science]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: Long Conference Paper
  url: https://www.aclweb.org/anthology/2021.naacl-main.376

url_pdf: 'https://www.aclweb.org/anthology/2021.naacl-main.376.pdf'
url_code: 'https://github.com/GU-DataLab/stance-detection-KE-MLM'
url_dataset: 'https://github.com/GU-DataLab/stance-detection-KE-MLM'
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
