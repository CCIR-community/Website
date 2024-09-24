---
title: 领域新闻
# nav:
#   order: 5
#  tooltip: 新闻
---

{% capture c1 %}

{% include portrait.html image="/images/CI_logo.png" link="http://www.cipsc.org.cn/" %}

{% include list_nav.html data="news" %}

{% endcapture %}

{% capture c2 %}

# <i class="fas fa-feather-alt"></i>领域新闻

<p></p>
{% include list_posts.html data="news" component="post-snippet" %}

{% endcapture %}
{% include two-col.html leftcol=c1 rightcol=c2 left=3 right=9 %}
