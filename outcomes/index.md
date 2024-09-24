---
title: 成果速递
# nav:
#   order: 4
# tooltip: 开源项目与数据
---

{% capture c1 %}

{% include portrait.html image="/images/CI_logo.png" link="http://www.cipsc.org.cn/" %}

{% include list_nav.html data="outcomes" %}

{% endcapture %}

{% capture c2 %}

# <i class="fas fa-feather-alt"></i>成果速递

<p></p>
{% include list_posts.html data="outcomes" component="post-snippet" %}

{% endcapture %}
{% include two-col.html leftcol=c1 rightcol=c2 left=3 right=9 %}
