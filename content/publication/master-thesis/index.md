
---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Retrieval Augmented Generative Task-Oriented Dialogue Systems"
authors:
- admin

date: 2022-07-29T15:48:21+01:00

# Schedule page publish date (NOT publication's date).
publishDate: 2022-07-22T15:48:21+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["7"]

# Publication name and optional abbreviated publication name.
publication: "Master Thesis"
publication_short: " Master Thesis"

abstract: "In this thesis, we study task-oriented dialogue systems that rely on efficient knowledge inference from background knowledge sources and dialogue history to satisfy a user goal. While the conventional modular architectures and the new age end-to-end architectures are the more established design choices for task-oriented dialogue systems, in this thesis, we propose a relatively simple retrieve-and-generate strategy for task-oriented dialogue systems. Our proposed approach enjoys the best of both architectures while addressing their respective limitations. We experiment with different retrieval techniques using sparse representations and dense embeddings. Considering the diversity of task-oriented dialogue datasets, we experiment with SMD, Camrest, and MultiWOZ-2.1. Furthermore, in view of the entity-rich nature of task-oriented dialogue systems, we question the typical process of introducing auxiliary objectives for better capturing entity awareness, with a simple alternative: adding a syntax embedding layer on top of the standard token embedding and position embedding layers, thereby explicitly adding syntactic knowledge into the model parameters. We propose to use a syntax-infused transformer, a model that explicitly leverages syntactic information by augmenting readily available entity-level metadata, e.g. part-of-speech tags. Despite its simplicity, the syntax-infused transformer is effective. On standard evaluation benchmarks for task-oriented dialogue systems, our proposed syntax-infused model exceeds our base model by an average of 13 Entity-F1 points and 2.8 BLEU points across the three datasets. At the same time, experimental results further confirm that our proposed model outperforms existing state-of-the-art models on the Entity-F1 metric. The empirical analysis further confirms the efficacy of our approach. Overall, our work proposes a relatively more interpretable, easily reproducible and lightweight model in terms of trainable parameters while achieving comparable performance with state-ofthe-art models. Additionally, we conduct robust error analysis for the generated responses together with the evaluation metrics and propose a handful of future research directions."

# Summary. An optional shortened abstract.
summary: "This thesis proposes a retrieve-and-generate strategy for task-oriented dialogue systems that combines the benefits of modular and end-to-end architectures. By incorporating syntax embeddings and leveraging entity-level metadata, the approach achieves improved performance on evaluation benchmarks and outperforms existing state-of-the-art models on the Entity-F1 metric."

tags: [ConversationalAI]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "https://scholar.google.com/scholar?q=Retrieval+Augmented+Generative+Task-oriented+Dialogue+Systems"
url_code: "https://github.com/soumya-ranjan-sahoo/Retrieve-n-Generate-ToD"
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
projects: 
- generate-counterfactuals-fairness

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
