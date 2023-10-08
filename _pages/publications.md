---
layout: page
permalink: /publications/
title: Publications
description: 
years: [2023, 2022, 2021, 2020, 2019, 2018, 2017, 2016]
nav: true
---

[[Google scholar](https://scholar.google.com/citations?hl=zh-CN&user=v4JiSqsAAAAJ)] | [[DBLP](https://dblp.org/pid/61/7717.html)] | [[View by topic](https://chanllon.github.io/research/)]

#### Preprints

- VSRQ: Quantitative Assessment Method for Safety Risk of Vehicle Intelligent Connected System. Tian Zhang, Wenshan Guan, Hao Miao, Xiujie Huang, Zhiquan Liu, Chaonan Wang, Quanlong Guan, Liangda Fang, Zhifei Duan. [[arxiv](https://arxiv.org/abs/2305.01898)]
- A Survey on Evaluation of Large Language Models. Yupeng Chang, Xu Wang, Jindong Wang, Yuan Wu, Kaijie Zhu, Hao Chen, Linyi Yang, Xiaoyuan Yi, Cunxiang Wang, Yidong Wang, Wei Ye, Yue Zhang, Yi Chang, Philip S. Yu, Qiang Yang, Xing Xie. [[arxiv](https://arxiv.org/abs/2307.03109)] [[code](https://github.com/MLGroupJLU/LLM-eval-survey)]

#### Books

<div class="publications">

{% for y in page.years %}
  {% bibliography -f books -q @*[year={{y}}]* %}
{% endfor %}

</div>

#### Papers

<div class="publications">

{% for y in page.years %}
  <div>{{y}}</div>
  {% bibliography -f pubs -q @*[year={{y}}]* %}
{% endfor %}

</div>
