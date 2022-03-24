---
widget: hero
headless: true
weight: 10
title: A Novel Video Class Incremental Learning Benchmark
hero_media: fig_horiz_consistency_demo.svg
design:
  background:
    gradient_angle: 0
    gradient_start: 'rgb(224,223,255)'
    gradient_end: 'rgb(153,238,255)'
    text_color_light: false
cta:
  url: https://arxiv.org/abs/2201.09381
  label: Read our paper
cta_alt:
  url: https://github.com/ojedaf/vCLIMB_Benchmark.git
  label: Our Code
cta_note:
  label:
advanced:
  css_class: fullscreen
---
<br>

<p style="font-size:18px;">Due to legal or technical constraints, and the fact that labeling data is expensive and time-consuming, real-world deep-learning pipelines would rarely involve a single fine-tuning stage. Instead, these pipelines could require the sequential fine-tuning of large models in a set of independent tasks that are learned sequentially. Under these conditions, deep neural networks suffer from what is known as catastrophic forgetting, where the fine-tuning on novel tasks significantly reduces the performance of the model in a previously learned task, and drift, where unseen training data does not fit the previously estimated class
distribution. Continual learning directly models such a scenario, by adapting a neural network model into a sequential series of tasks. We focus on a special case of CL: class incremental learning (CIL), where the labels and data are mutually exclusive between tasks, training data is available only for the current task, and there are no tasks ids.

</p>

<br>

<!-- <a class="github-button" href="https://github.com/wowchemy/wowchemy-hugo-modules" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star Wowchemy Website Builder for Hugo">Star Wowchemy Website Builder for Hugo</a><br><a class="github-button" href="https://github.com/wowchemy/starter-hugo-online-course" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star the Online Course template">Star the Online Course template</a><script async defer src="https://buttons.github.io/buttons.js"></script> -->
