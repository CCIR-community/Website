---
title: 专委成员
nav:
  order: 2
  # tooltip: 团队成员
---
{% capture c2 %}

## 现任常委

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: commitee_current"
%}


{:center}
## 历届主任

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: commitee_former"
%}


## 前沿工作组

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: group_frontier"
%}

## 宣传工作组

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: group_publicity"
%}

## 评测工作组

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: group_challenge"
%}

## 专委委员

{%
  include list.html
  data="members"
  component="member"
  filters="role: regular_member"
%}

{% endcapture %}

{% capture c1 %}

{% include portrait.html image="/images/CI_logo.png" link="http://www.cipsc.org.cn/" %}

<div class="sticky_sidebar">
  <ul class="no-padding margin-left-10 organizers-type-list hidden-xs" id="sidebar-nav">
    <li class=""><a href="#现任常委">现任常委</a></li>
    <li class=""><a href="#历届主任">历届主任</a></li>
    <li class=""><a href="#前沿工作组">前沿工作组</a></li>
    <li class=""><a href="#宣传工作组">宣传工作组</a></li>
    <li class=""><a href="#评测工作组">评测工作组</a></li>
    <li class=""><a href="#专委委员">专委委员</a></li>
  </ul>
</div>

{% endcapture %}

{% include two-col.html leftcol=c1 rightcol=c2 left=3 right=9 %}