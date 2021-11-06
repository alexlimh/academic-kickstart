---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Multi-Task Dense Retrieval via Model Uncertainty Fusion for Open-Domain Question Answering"
authors: ["**Minghan Li**&ast;", "Ming Li", "Kun Xiong", "Jimmy Lin"]
date: 2021-08-28T18:42:17-04:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-08-28T18:42:17-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "EMNLP 2021"
publication_short: "EMNLP 2021"

abstract: "*Findings of the 2021 Conference on Empirical Methods in Natural Language Processing (EMNLP)*"

# Summary. An optional shortened abstract.
summary: 
# "Multi-task dense retrieval models can be used to retrieve documents from a common corpus (e.g., Wikipedia) for different open-domain question-answering (QA) tasks. However, Karpukhin et al. (2020) shows that jointly learning different QA tasks with one dense model is not always beneficial due to corpus inconsistency. For example, SQuAD only focuses on a small set of Wikipedia articles while datasets like NQ and Trivia cover more entries, and joint training on their union can cause performance degradation. To solve this problem, we propose to train individual dense passage retrievers (DPR) for different tasks and aggregate their predictions during test time, where we use uncertainty estimation as weights to indicate how probable a specific query belongs to each expert’s expertise. Our method reaches state-of-the-art performance on 5 benchmark QA datasets, with up to 10% improvement in top-100 accuracy compared to a joint-training multi-task DPR on SQuAD. We also show that our method handles corpus inconsistency better than the joint-training DPR on a mixed subset of different QA datasets. Code and data are available at https://github.com/alexlimh/DPR_MUF."

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

url_pdf: https://aclanthology.org/2021.findings-emnlp.26/
url_code: https://github.com/alexlimh/DPR_MUF
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
