---
title: 团队成员
nav:
  order: 3
  tooltip: 我们的团队
---

# {% include icon.html icon="fa-solid fa-users" %}团队成员

花果山实验室拥有一支优秀的科研团队，我们致力于前沿科研探索，推动学术创新。

{% include section.html %}

## 负责人

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}

## 研究人员

{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

{% include section.html background="images/background.jpg" dark=true %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
