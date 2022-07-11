---
abstract: >-
  Stochastic sampling of light transport paths is key to Monte Carlo forward
  rendering, and previous studies have led to mature techniques capable of
  drawing high-contribution light paths in complex scenes. These sampling
  techniques have also been applied to differentiable rendering.


  In this paper, we demonstrate that path sampling techniques developed for forward rendering can become inefficient for differentiable rendering of glossy materials---especially when estimating derivatives with respect to global scene geometries. To address this problem, we introduce antithetic sampling of BSDFs and light-transport paths, allowing significantly faster convergence and can be easily integrated into existing differentiable rendering pipelines. We validate our method by comparing our derivative estimates to those generated with existing unbiased techniques. Further, we demonstrate the effectiveness of our technique by providing equal-quality and equal-time comparisons with existing sampling methods.
slides: example
url_pdf: ""
publication_types:
  - "1"
authors:
  - Cheng Zhang
  - Zhao Dong
  - Michael Doggett
  - Shuang Zhao
author_notes: []
publication: ACM Transactions on Graphics (SIGGRAPH 2021), 40(4), August 2021
summary: ""
url_dataset: ""
url_project: ""
publication_short: ""
url_source: ""
url_video: ""
title: Antithetic Sampling for Monte Carlo Differentiable Rendering
doi: ""
featured: false
tags: []
projects:
  - example
image:
  caption: ""
  focal_point: ""
  preview_only: false
date: 2022-07-11T16:55:59.067Z
url_slides: ""
publishDate: 2017-01-01T00:00:00Z
url_poster: ""
url_code: ""
---
