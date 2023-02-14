---
title: 首页
nav:
  order: 1
---

# 中国中文信息学会信息检索专委会

{% capture c1 %}
| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |
{% endcapture %}

{% capture c2 %}
{% include timeline.html data="news-timeline" component="citation" style="rich" %}
{% endcapture %}

{% include two-col.html leftcol=c1 rightcol=c2 left=4 right=8 %}

