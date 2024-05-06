---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

苏昊，副研究员，硕士生导师。博士毕业于北京航空航天大学虚拟现实技术与系统国家重点实验室。长期从事生成式人工智能、强化学习、计算机视觉和图形学等研究工作。在CVPR、AAAI、ACM MM、TCSVT、TMM、TOMM等期刊及会议发表论文，曾受邀担任CVPR、AAAI、ACM MM、TMM、TCSVT等期刊及会议审稿人。

主要研究方向：生成式人工智能、强化学习、计算机视觉和图形学

 <a href='https://scholar.google.com/citations?user=yf4XwjEAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>






