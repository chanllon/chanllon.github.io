---
layout: page
permalink: /publications/
title: Publications
description: 
years: [2026, 2025, 2024, 2023, 2022, 2021, 2020, 2019]
nav: true
---

[[Google scholar](https://scholar.google.com/citations?hl=zh-CN&user=v4JiSqsAAAAJ)] | [[DBLP](https://dblp.org/pid/61/7717.html)] | [[View by topic](https://chanllon.github.io/research/)]

#### Preprints

- Reproducible Vision-Language Models Meet Concepts Out of Pre-Training. Ziliang Chen, Xin Huang, Xiaoxuan Fan, Keze Wang, Yuyu Zhou, Quanlong Guan, Liang Lin. [[arxiv](https://arxiv.org/)]
- Automatic Verification of Linear Integer Planning Programs via Forgetting in LIAUPF. Liangda Fang, Shikang Chen, Xiaoman Wang, Xiaoyou Lin, Chenyi Zhang, Qingliang Chen, Quanlong Guan∗,  Kaile Su†.
- [[Doi](https://dl.acm.org/doi/abs/10.1145/3511808.3557096)] [[code](https://github.com/chanllon)]

<!-- #### Books

<div class="publications">

{% for y in page.years %}
  {% bibliography -f books -q @*[year={{y}}]* %}
{% endfor %}

</div> -->

#### Selected Papers

<div class="publications">

{% for y in page.years %}
  <div>{{y}}</div>
  
  {% bibliography -f pubs -q @*[year={{y}}]* %}
 
{% endfor %}

</div>
