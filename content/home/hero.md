---
widget: hero
headless: true
weight: 10
title: A Novel Video Class Incremental Learning Benchmark
hero_media: student.svg
design:
  background:
    gradient_angle: 0
    gradient_start: 'rgb(224,223,255)'
    gradient_end: 'rgb(153,238,255)'
    text_color_light: false
cta:
  url: course/
  label: Explore our courses
  icon_pack: fas
  icon: user-graduate
cta_alt:
  url:
  label:
cta_note:
  label:
advanced:
  css_class: fullscreen
---
<br>

Continual learning (CL) is under-explored in the video domain. The few existing works contain splits with imbalanced class distributions over the tasks, or study the problem in unsuitable datasets. We introduce vCLIMB, a novel video continual learning benchmark. vCLIMB is a standardized test-bed to analyze catastrophic forgetting of deep models in video continual learning. In contrast to previous work, we focus on class incremental continual learning with models trained on a sequence of disjoint tasks, and distribute the number of classes uniformly across the tasks. We perform in-depth evaluations of existing CL methods in vCLIMB, and observe two unique challenges in video data. The selection of instances to store in episodic memory is performed at the frame level. Second, untrimmed training data influences the effectiveness of frame sampling strategies. We address these two challenges by proposing a temporal consistency regularization that can be applied on top of memory-based continual learning methods. Our approach significantly improves the baseline, by up to 24% on the untrimmed continual learning task. To streamline and foster future research in video continual learning, we will publicly release the code for our benchmark and method.

<a class="github-button" href="https://github.com/wowchemy/wowchemy-hugo-modules" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star Wowchemy Website Builder for Hugo">Star Wowchemy Website Builder for Hugo</a><br><a class="github-button" href="https://github.com/wowchemy/starter-hugo-online-course" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star the Online Course template">Star the Online Course template</a><script async defer src="https://buttons.github.io/buttons.js"></script>
