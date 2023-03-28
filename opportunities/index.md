---
title: 加入我们
nav:
  order: 8
  children:
    - 正式委员
    - 通讯委员
---
{% capture c1 %}

{% include portrait.html image="/images/CI_logo.png" link="http://www.cipsc.org.cn/" %}

<div class="sticky_sidebar">
  <ul class="no-padding margin-left-10 organizers-type-list hidden-xs" id="sidebar-nav">
    <li class=""><a href="{{ "/opportunities/信息检索专委会委员申请表.doc" | relative_url }}">信息检索专委会委员申请表</a></li>
    <li class=""><a href="{{ "/opportunities/信息检索专委会通讯委员申请表.doc" | relative_url }}">信息检索专委会通讯委员申请表</a></li>
  </ul>
</div>

{% endcapture %}

{% capture c2 %}

# <i class="fas fa-envelope"></i>新委员申请

为进一步加强专委会建设工作，新委员应具备以下条件：

1. 具备中国中文信息学会会员资格；
2. 目前在不超过两个中国中文信息学会专委会担任委员；
3. 在信息检索领域做出有影响力的科研工作；
4. 积极参加专委会过去举办的主要学术活动；
5. 未来愿意积极为专委会建设工作贡献力量；
6. 获得两位专委会现任委员推荐。

专委会按照季度发展新委员。第一季度委员申请截止时间是2月28日，执委会将在3月工作会议上集中审批委员申请，在3月份公布通过审批的新委员名单。第二季度委员申请截止时间是5月31日，第三季度截止时间是8月31日，第四季度截止时间是11月30日。
 
欢迎各位委员推荐信息检索优秀学者申请加入专委会。申请人需填写的[委员申请表]({{ "/opportunities/信息检索专委会委员申请表.doc" | relative_url }})或[通讯委员申请表]({{ "/opportunities/信息检索专委会通讯委员申请表.doc" | relative_url }})，发送至TODO

{% endcapture %}
{% include two-col.html leftcol=c1 rightcol=c2 left=3 right=9 %}