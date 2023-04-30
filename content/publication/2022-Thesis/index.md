---
title: "Detecting and Understanding of Information Pollution on Social Media"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin

date: "2022-12-09T00:00:00Z"
doi: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *ProQuest Dissertations and Theses*
# publication_short: In ***XXX***

abstract: Social media and the web have become primary sources for obtaining information and news. Given the speed and spread of information on social media, effects of poor-quality information, especially with respect to health-related information, can be consequential. In recent years, researchers have been working on detecting different types of poor-quality information, e.g. fake news and misinformation, and identifying levels of support. Knowledge of both of these types of information can be used to mitigate the negative effects of this information pollution. Research on information pollution within computer science is growing rapidly; however, the state of the art still has a number of limitations, including the inability to accurately identify information pollution in noisy domains like social media where high-quality labels are limited and information spreads rapidly. <br><br>In this dissertation, we aim to address some of the aforementioned challenges, specifically on two types of information pollution, spam and misinformation. We show on different Twitter data sets that context-specific spam exists and is identifiable using only content-based features, and present a comparative study of different detection algorithms in a low resource setting. Next, we review literature on misinformation detection and discuss the need for building bridges between misinformation detection research in computer science and research in other disciplines. To detect misinformation on Twitter in a resource-constrained environment, we develop a novel reinforcement learning framework for weak supervision and show that our model outperforms baseline models. To improve detection of multiple myths simultaneously and exploit information learned for different myth themes, we propose a novel cooperative learning method for multi-agent reinforcement learning, thereby improving the training process in our reinforcement learning framework. To understand whether there is support for the misinformation, we study stance detection. We propose a stance detection algorithm that uses the log-odds-ratio algorithm to identify distinguishable stance words, then model a novel attention mechanism that focuses on these words. We show that our approach outperforms the state-of-the-art models on Twitter data sets about the 2020 US Presidential election. Next, we develop and release a pre-trained language model trained on a large amount of social media data about the US election in order to support those studying political (mis)information. <br><br>Finally, we publish the models, data sets, and code, enabling future research on spam, misinformation, and stance detection. All of these contributions reduce the existing knowledge gaps, bringing us closer to a world free of information pollution.

# Summary. An optional shortened abstract.
summary: 

tags: [NLP, misinformation, stance-detection, spam-detection, data-mining, machine-learning, deep-learning, data-efficient, reinforcement-learning, cooperative-learning, multi-agent-reinforcement-learning, twitter, language-modeling]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: PhD Dissertation
  url: https://www.proquest.com/docview/2768180618

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
