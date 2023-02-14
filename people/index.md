---
title: 专委成员
nav:
  order: 1
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
## 历任常委

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
  filters="role: phd"
%}

{% endcapture %}

{% capture c1 %}

{% endcapture %}

{% include two-col.html leftcol=c1 rightcol=c2 left=3 right=9 %}