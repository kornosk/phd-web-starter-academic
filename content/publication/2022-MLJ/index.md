---
title: "Traditional and Context-specific Spam Detection in Low Resource Settings"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Lisa Singh
- Ceren Budak

date: "2022-06-09T00:00:00Z"
doi: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Machine Learning*
publication_short: In ***Machine Learning***

abstract: Social media data has a mix of high and low-quality content. One form of commonly studied low-quality content is spam. Most studies assume that spam is context-neutral. We show on different Twitter data sets that context-specific spam exists and is identifiable. We then compare multiple traditional machine learning models and a neural network model that uses a pre-trained BERT language model to capture contextual features for identifying spam, both traditional and context-specific, using only content-based features. The neural network model outperforms the traditional models with an F1 score of 0.91. Because spam training data sets are notoriously imbalanced, we also investigate the impact of this imbalance and show that simple Bag-of-Words models are best with extreme imbalance, but a neural model that fine- tunes using language models from other domains significantly improves the F1 score, but not to the levels of domain-specific neural models. This suggests that the strategy employed may vary depending upon the level of imbalance in the data set, the amount of data available in a low resource setting, and the prevalence of context-specific spam vs. traditional spam. Finally, we make our data sets available for use by the research community.

# Summary. An optional shortened abstract.
summary: We propose a novel taxonomy for false information on social media and a new concept of context-specific spam. We release both data and models.

tags: [spam-detection, NLP, language-modeling, BERT, twitter, false-information]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: Journal Article
  url: https://doi.org/10.1007/s10994-022-06176-x

url_pdf: 'https://rdcu.be/cPly3'
url_code: 'https://github.com/GU-DataLab/context-spam'
url_dataset: 'https://portals.mdi.georgetown.edu/public/spam'
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
