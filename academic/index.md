---
title: 学术活动
nav:
  order: 3
  # tooltip: SIGIR CAll For Papers
---

{% capture c1 %}

{% include portrait.html image="/images/CI_logo.png" link="http://www.cipsc.org.cn/" %}

{% include list_nav.html data="academic" %}

{% endcapture %}

{% capture c2 %}

# <i class="fas fa-feather-alt"></i>学术活动
<p></p>
{% include list_posts.html data="academic" component="post-snippet" %}

{% endcapture %}
{% include two-col.html leftcol=c1 rightcol=c2 left=3 right=9 %}