---
title: 研究成果
nav:
  order: 1
  tooltip: 论文发表
---

# {% include icon.html icon="fa-solid fa-microscope" %}研究成果

本页面展示实验室的论文发表，自动按年份分组显示。

{% include section.html %}

## 精选论文

{% include citation.html lookup="Open collaborative writing with Manubot" style="rich" %}

{% include section.html %}

## 全部论文

<!-- 搜索框 - 可以按标题、作者、年份等搜索 -->
{% include search-box.html %}

<!-- 论文统计信息 -->
{% include search-info.html %}

<!-- 论文列表 - 自动按年份分组（2025、2024、2023...） -->
{% include list.html data="citations" component="citation" style="rich" %}
