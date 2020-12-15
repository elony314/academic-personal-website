---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'To Follow or not to Follow: Selective Imitation Learning from Observations'
subtitle: ''
summary: ''
authors:
- Youngwoon Lee
- Edward S. Hu
- admin
- Joseph J. Lim
tags: []
categories: []
date: '2020-05-01'
lastmod: 2020-12-14T22:20:47-08:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

links:
 - name: Website
   url: 'https://clvrai.com/silo'
 - name: Spotlight
   url: "https://www.youtube.com/watch?v=b7StSnt85S4&feature=youtu.be&t=12591"

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2020-12-15T06:38:21.253535Z'
publication_types:
- '1'
abstract: Learning from demonstrations is a useful way to transfer a skill from one agent to another. While most imitation learning methods aim to mimic an expert skill by following the demonstration step-by-step, imitating every step in the demonstration often becomes infeasible when the learner and its environment are different from the demonstration. In this paper, we propose a method that can imitate a demonstration composed solely of observations, which may not be reproducible with the current agent. Our method, dubbed selective imitation learning from observations (SILO), selects reachable states in the demonstration and learns how to reach the selected states. Our experiments on both simulated and real robot environments show that our method reliably performs a new task by following a demonstration. Videos and code are available at [this https URL](https://clvrai.com/silo).
publication: '*Conference on Robot Learning (CoRL)*'
url_pdf: http://proceedings.mlr.press/v100/lee20a.html
---
