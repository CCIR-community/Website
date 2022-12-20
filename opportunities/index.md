---
title: Opportunities
nav:
  order: 8
  children:
    - news
    - news2
    - news3
---

# <i class="fas fa-envelope"></i>Contact 联系我们

THUIR is part of the [Department of Computer Science & Technology](https://www.cs.tsinghua.edu.cn/csen/), at [Tsinghua University](https://www.tsinghua.edu.cn/en/).
We are located on the FIT building 1-506, Tsinghua University.

清华大学智能技术与系统国家重点实验室信息检索课题组隶属于清华大学计算机系，地址：中国北京清华大学FIT楼1-506.
{%
  include link.html
  type="address"
  icon=""
  text="Maps"
  tooltip="Our location on map for easy navigation"
  link="https://surl.amap.com/cx4NrTI4g1c"
  style="button"
%}
{:.center}

{% include section.html %}

{% capture text %}
THUIR课题组每年面向本校、外校招收博士生3-5名左右，硕士生1名左右，具体依当年情况确定。目前组内招收博士研究方向包括搜索、推荐、排序等大方向，具体包括网页检索、用户行为分析、数据挖掘、脑机接口、法律检索、排序模型、新模态推荐、信息表示学习、信息可靠性与公平性等细分领域，具体参看[课题组教师介绍](../people/)。欢迎感兴趣的同学直接通过以下链接邮件联系课题组内研究生导师。

{%
  include link.html
  link="mailto:msp@tsinghua.edu.cn"
  text="马少平 教授"
  icon="fas fa-envelope"
  style="button"
%}
{%
  include link.html
  link="mailto:z-m@mail.tsinghua.edu.cn"
  text="张敏 教授"
  icon="fas fa-envelope"
  style="button"
%}
{%
  include link.html
  link="mailto:yiqunliu@tsinghua.edu.cn"
  text="刘奕群 教授"
  icon="fas fa-envelope"
  style="button"
%}
{%
  include link.html
  link="mailto:aiqy@tsinghua.edu.cn"
  text="艾清遥 助理教授"
  icon="fas fa-envelope"
  style="button"
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/grad_admin.jpg"
  title="Grad Student Admission 研究生招生"
  text=text
%}

{% include section.html %}

{% capture text %}
THUIR课题组长期招募博士后，欢迎有信息检索、自然语言处理、数据挖掘等方面研究经验的年轻学者加入我们的队伍！详情可参见[THUIR博士后申请](https://mp.weixin.qq.com/s/6_NKkVI9NFWUi6PZJJWX5A)。

{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/postdoc_hire.jpg"
  title="PostDoc Position 博士后招聘"
  text=text
%}

{% include section.html %}

{% capture col1 %}
{%
  include figure.html
  image="images/THU-CS.jpg"
  caption="Department of CST"
%}
{% endcapture %}
{% capture col2 %}
{%
  include figure.html
  image="images/THU.jpg"
  caption="Tsinghua University"
%}
{% endcapture %}
{% include two-col.html col1=col1 col2=col2 %}
