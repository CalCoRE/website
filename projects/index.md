---
title: Projects
nav:
  order: 2
  tooltip: More about our work
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

Our research and development initiatives span classroom-ready software design, empirical data science curriculum development, and teacher professional training. Explore our featured projects and tools below.

{% include tags.html tags="publication, resource, website" %}

{% include search-info.html %}

{% include section.html %}

## Featured

{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{% include section.html %}

## More

{% include list.html component="card" data="projects" filter="!group" style="small" %}
