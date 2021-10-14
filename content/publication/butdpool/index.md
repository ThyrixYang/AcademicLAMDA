---
title: "Bottom-Up and Top-Down Graph Pooling"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- yangjq
- De-Chuan Zhan
- Xin-Chun Li

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2020-05-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-05-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Proceedings of the 24th Pacific-Asia Conference on Knowledge Discovery and Data Mining
publication_short: PAKDD’20

abstract: Pooling layers are crucial components for efficient deep representation learning. As to graph data, however, it’s not trivial to decide which nodes to retain in order to represent the high-level structure of a graph. Recently many different graph pooling methods have been proposed. However, they all rely on local features to conduct global pooling over all nodes, which contradicts poolings in CNNs that only use local features to conduct local pooling. We analyze why this may hinder the performance of graph pooling, then propose a novel graph pooling method called Bottom-Up and Top-Down graph POOLing (BUTDPool). BUTDPool aims to learn a more fine-grained pooling criterion based on coarse global structure information produced by a bottom-up pooling layer, and can enhance local features with global features. Specifically, we propose to use one or multiple pooling layers with a relatively high retain ratio to produce a coarse high-level graph. Injecting the high-level information back into low-level representation, BUTDPool enhances learning a better pooling criterion. Experiments demonstrate the superior performance of the proposed method over compared method
# Summary. An optional shortened abstract.
# summary: ss

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: ppt
#   url: http://example.org

url_pdf: 'https://gitlab.com/thyrix/public_assets/-/blob/master/papers/PAKDD20_BUTDPool.pdf'
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
