---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Discrepant Semantic Diffusion Boosts Transfer Learning Robustness
subtitle: ''
summary: ''
authors:
- Yajun Gao
- Shihao Bai
- Xiaowei Zhao
- Ruihao Gong
- Yan Wu
- Yuqing Ma
tags: []
categories: []
date: '2023-01-01'
lastmod: 2024-02-27T22:50:35+08:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2024-02-27T14:50:35.287005Z'
publication_types:
- article-journal
abstract: Transfer learning could improve the robustness and generalization of the
  model, reducing potential privacy and security risks. It operates by fine-tuning
  a pre-trained model on downstream datasets. This process not only enhances the model’s
  capacity to acquire generalizable features but also ensures an effective alignment
  between upstream and downstream knowledge domains. Transfer learning can effectively
  speed up the model convergence when adapting to novel tasks, thereby leading to
  the efficient conservation of both data and computational resources. However, existing
  methods often neglect the discrepant downstream–upstream connections. Instead, they
  rigidly preserve the upstream information without an adequate regularization of
  the downstream semantic discrepancy. Consequently, this results in weak generalization,
  issues with collapsed classification, and an overall inferior performance. The main
  reason lies in the collapsed downstream–upstream connection due to the mismatched
  semantic granularity. Therefore, we propose a discrepant semantic diffusion method
  for transfer learning, which could adjust the mismatched semantic granularity and
  alleviate the collapsed classification problem to improve the transfer learning
  performance. Specifically, the proposed framework consists of a Prior-Guided Diffusion
  for pre-training and a discrepant diffusion for fine-tuning. Firstly, the Prior-Guided
  Diffusion aims to empower the pre-trained model with the semantic-diffusion ability.
  This is achieved through a semantic prior, which consequently provides a more robust
  pre-trained model for downstream classification. Secondly, the discrepant diffusion
  focuses on encouraging semantic diffusion. Its design intends to avoid the unwanted
  semantic centralization, which often causes the collapsed classification. Furthermore,
  it is constrained by the semantic discrepancy, serving to elevate the downstream
  discrimination capabilities. Extensive experiments on eight prevalent downstream
  classification datasets confirm that our method can outperform a number of state-of-the-art
  approaches, especially for fine-grained datasets or datasets dissimilar to upstream
  data (e.g., 3.75% improvement for Cars dataset and 1.79% improvement for SUN dataset
  under the few-shot setting with 15% data). Furthermore, the experiments of data
  sparsity caused by privacy protection successfully validate our proposed method’s
  effectiveness in the field of artificial intelligence security.
publication: '*Electronics*'
doi: 10.3390/electronics12245027
links:
- name: URL
  url: https://www.mdpi.com/2079-9292/12/24/5027
---
