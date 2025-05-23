---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Extremely Low-Bit Convolution Optimization for Quantized Neural Network on
  Modern Computer Architectures
subtitle: ''
summary: ''
authors:
- Qingchang Han
- Yongmin Hu
- Fengwei Yu
- Hailong Yang
- Bing Liu
- Peng Hu
- Ruihao Gong
- Yanfei Wang
- Rui Wang
- Zhongzhi Luan
- Depei Qian
tags:
- NVIDIA GPU
- Quantized Neural Network
- Extremely Low-bit Convolution
- Computation Optimization
- ARM CPU
categories: []
date: '2020-01-01'
lastmod: 2022-03-27T15:27:44+08:00
featured: false
draft: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=aC--JOyqRPs'

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
publishDate: '2022-03-27T07:29:00.583344Z'
publication_types:
- paper-conference
abstract: 'With the continuous demand for higher accuracy of deep neural networks,
  the model size has increased significantly. Quantization is one of the most widely
  used model compression methods, which can effectively reduce the model size without
  severe accuracy loss. Modern processors such as ARM CPU and NVIDIA GPU have already
  provided the support of low-bit arithmetic instructions. However, there lack efficient
  and practical optimizations for convolution computation towards extremely low-bit
  on ARM CPU (e.g., 2 ∼ 8-bit) and NVIDIA GPU (e.g., 4-bit and 8-bit). This paper
  explores the performance optimization methods of extremely low-bit convolution on
  diverse architectures. On ARM CPU, we propose two instruction schemes for 2 ∼ 3-bit
  and 4 ∼ 8-bit convolution with corresponding register allocation methods. In addition,
  we re-design the GEMM computation with data padding and packing optimizations. We
  also implement winograd algorithm for convolution with some specific bit width (e.g.,
  4 ∼ 6-bit) to achieve higher performance. On NVIDIA GPU, we propose a data partition
  mechanism and multi-level memory access optimizations, to better adapt the computation
  to GPU thread and memory hierarchy. We also propose quantization fusion to eliminate
  unnecessary data access. The experiment results demonstrate our implementations
  achieve better performance of extremely low-bit convolution compared to the state-of-the-art
  frameworks and libraries such as ncnn and cuDNN. To the best of our knowledge, this
  is the first work that provides efficient implementations of extremely low-bit convolutions
  covering 2 ∼ 8-bit on ARM CPU and 4-bit/8-bit on NVIDIA GPU. '
publication: '*49th International Conference on Parallel Processing - ICPP*'
doi: 10.1145/3404397.3404407
links:
- name: URL
  url: https://doi.org/10.1145/3404397.3404407
---
