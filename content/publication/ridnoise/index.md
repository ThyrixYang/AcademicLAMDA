---
title: "RID-Noise: Towards Robust Inverse Design under Noisy Environments"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- yangjq
- Ke-Bin Fan
- Hao Ma
- De-Chuan Zhan

date: "2022-02-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-02-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Proceedings of the 36th AAAI Conference on Artificial Intelligence
publication_short: In AAAI'22

abstract: From an engineering perspective, a design should not only perform well in an ideal condition, but should also resist noises. Such a design methodology, namely robust design, has been widely implemented in the industry for product quality control. However, classic robust design requires a lot of evaluations for a single design target, while the results of these evaluations could not be reused for a new target. To achieve data-efficient robust design, we propose Robust Inverse Design under Noise (RID-Noise), which can utilize existing data to train a conditional invertible neural network. Specifically, we estimate the robustness of a design parameter by its predictability, measured by the prediction error of a forward neural network. We also define a sample-wise weight, which can be used in the maximum weighted likelihood estimation of an inverse model based on a conditional invertible neural network. With the visual results from experiments, we clearly justify how RID-Noise works by learning the distribution and robustness from data. Further experiments on several real-world benchmark tasks with noises confirm that our method is more effective than other state-of-the-art inverse design methods.


summary: From an engineering perspective, a design should not only perform well in an ideal condition, but should also resist noises. Such a design methodology, namely robust design, has been widely implemented in the industry for product quality control. To achieve data-efficient robust design, we propose Robust Inverse Design under Noise (RID-Noise), which can utilize existing data to train a conditional invertible neural network. With the visual results from experiments, we clearly justify how RID-Noise works by learning the distribution and robustness from data. Further experiments on several real-world benchmark tasks with noises confirm that our method is more effective than other state-of-the-art inverse design methods.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: ppt
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2112.03912'
url_code: 'https://github.com/ThyrixYang/rid-noise-aaai22'
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
