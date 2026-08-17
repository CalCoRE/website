---
title: News
nav:
  order: 4
  tooltip: Latest updates and announcements
---

# {% include icon.html icon="fa-regular fa-newspaper" %}News and Announcements

Stay up to date with the latest research updates, publications, and announcements from the Computing, Reasoning, and Expression (CoRE) Lab at UC Berkeley.

{% include section.html %}

{% include search-box.html %}

{% include search-info.html %}

{% include list.html data="posts" component="post-excerpt" filter="categories && categories.include?('news')" %}
