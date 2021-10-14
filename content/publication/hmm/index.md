---
title: "Corporate Relative Valuation using Heterogeneous Multi-Modal Graph Neural Network"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Yang Yang
- yangjq
- Ran Bao
- De-Chuan Zhan
- Hengshu Zhu
- Xiao-Ru Gao
- Hui Xiong

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2021-01-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: IEEE Transactions on Knowledge and Data Engineering
publication_short: TKDE

abstract: Corporate relative valuation (CRV) refers to the process of comparing a company's value from company products, core staff and other related information, so that we can assess the company's market value, which is critical for venture capital firms. Traditionally, relative valuation methods heavily rely on tedious and expensive human efforts, especially for non-publicly listed companies. However, the availability of information about company's invisible assets, such as patents, talent, and investors, enables a new paradigm for learning and evaluating corporate relative values automatically. Indeed, in this paper, we reveal that, if the companies and their core members are formed as a heterogeneous graph and the attributes of different nodes include semantically-rich multi-modal data, it is able to extract a latent embedding for each company. Along this line, we develop an end-to-end heterogeneous multi-modal graph neural network method, named HM<formula><tex>$^2$</tex></formula>. Specifically, HM<formula><tex>$^2$</tex></formula> firstly perform the representation learning for heterogeneous neighbors of input company by taking relationships among nodes into consideration, which aggregates node attributes via linkage-aware multi-head attention mechanism, rather than multi-instance based methods. Then, HM<formula><tex>$^2$</tex></formula> adopts the self-attention network to aggregate different modal embeddings for final prediction, and employs dynamic triplet loss with embeddings of competitors as the constraint.
# Summary. An optional shortened abstract.
# summary: ss

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://gitlab.com/thyrix/public_assets/-/raw/master/papers/Corporate_Relative_Valuation_using_Heterogeneous_Multi-Modal_Graph_Neural_Network.pdf?inline=false'
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
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
<!-- 
{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}} -->

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
