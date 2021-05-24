---
title: "Towards Automatic Comparison of Data Privacy Documents: A Preliminary Experiment on GDPR-like Laws"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Yaguang Liu

date: "2021-05-21T00:00:00Z"
doi: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: In *arXiv*
publication_short: In ***arXiv***

abstract: General Data Protection Regulation (GDPR) becomes a standard law for data protection in many countries. Currently, twelve countries adopt the regulation and establish their GDPR-like regulation. However, to evaluate the differences and similarities of these GDPRlike regulations is time-consuming and needs a lot of manual effort from legal experts. Moreover, GDPR-like regulations from different countries are written in their languages leading to a more difficult task since legal experts who know both languages are essential. In this paper, we investigate a simple natural language processing (NLP) approach to tackle the problem. We first extract chunks of information from GDPR-like documents and form structured data from natural language. Next, we use NLP methods to compare documents to measure their similarity. Finally, we manually label a small set of data to evaluate our approach. The empirical result shows that the BERT model with cosine similarity outperforms other baselines. Our data and code are publicly available.

tags: [gdpr, gdpr-like, personal-data-protection, data-privacy, legal-document-analysis, document-similarity, natural-language-processing, nlp]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: Preprint
  url: https://arxiv.org/abs/2105.10117

url_pdf: 'https://arxiv.org/pdf/2105.10117.pdf'
url_code: 'https://github.com/kornosk/GDPR-similarity-comparison'
url_dataset: 'https://github.com/kornosk/GDPR-similarity-comparison'
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