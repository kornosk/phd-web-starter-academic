---
title: "PoliBERTweet: A Pre-trained Language Model for Analyzing Political Content on Twitter"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Lisa Singh

date: "2022-06-20T00:00:00Z"
doi: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the Language Resources and Evaluation Conference  (LREC)*
publication_short: In ***LREC***

abstract: Transformer-based models have become the state-of-the-art for numerous natural language processing (NLP) tasks, especially for noisy data sets, including social media posts. For example, BERTweet, pre-trained RoBERTa on a large amount of Twitter data, has achieved state-of-the-art results on several Twitter NLP tasks. We argue that it is not only important to have general pre-trained models for a social media platform, but also domain-specific ones that better capture domain-specific language context. Domain-specific resources are not only important for NLP tasks associated with a specific domain, but they are also useful for understanding language differences across domains. One domain that receives a large amount of attention is politics, more specifically political elections. Towards that end, we release PoliBERTweet, a pre-trained language model trained from BERTweet on over 83M US 2020 election-related English tweets. While the construction of the resource is fairly straightforward, we believe that it can be used for many important downstream tasks involving language, including political misinformation analysis and election public opinion analysis. To show the value of this resource, we evaluate PoliBERTweet on different NLP tasks. The results show that our model outperforms general-purpose language models in domain-specific contexts, highlighting the value of domain-specific models for more detailed linguistic analysis. We also extend other existing language models with a sample of these data and show their value for presidential candidate stance detection, a context-specific task. We release PoliBERTweet and these other models to the community to advance interdisciplinary research related to Election 2020.

# Summary. An optional shortened abstract.
summary: We propose pre-trained language models for political Twitter data. We evaluate all models and report results. We release both data and pre-trained models.

tags: [politics, NLP, language-model, transformer, BERT, BERTweet, RoBERTa, election-2020, twitter]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: Short Conference Paper
  url: https://aclanthology.org/2022.lrec-1.801

url_pdf: 'https://aclanthology.org/2022.lrec-1.801.pdf'
url_code: 'https://github.com/GU-DataLab/PoliBERTweet'
url_dataset: 'https://portals.mdi.georgetown.edu/public/polibertweet-masked-token-prediction'
url_poster: 'https://drive.google.com/file/d/1h4TizoBex4siD2qTEkGobmLX5jfoehUe/view?usp=sharing'
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://drive.google.com/file/d/1HquyiEl5u9De5fxvV9_O6s-Vj2NgLgAW/view?usp=sharing'

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
