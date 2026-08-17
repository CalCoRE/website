---
title: Resources
nav:
  order: 1
  tooltip: Musings and miscellany
---

# {% include icon.html icon="fa-solid fa-feather-pointed" %}Resources for Teaching and Design

Explore our collection of discussion guides, datasets, lesson slides, and interactive notebook modules designed to integrate computational thinking and data investigation into classrooms. Search or filter below by project, target level, and resource type.

{% include section.html %}

{% include search-box.html %}

<div class="tags-grouped">
  <div class="tag-group">
    <span class="tag-group-label">Project:</span>
    {% include tags.html tags="choosy, syw, wds, moda, rivulet" %}
  </div>
  <div class="tag-group">
    <span class="tag-group-label">Level:</span>
    {% include tags.html tags="middle school, high school, teachers, college" %}
  </div>
  <div class="tag-group">
    <span class="tag-group-label">Type:</span>
    {% include tags.html tags="datasets, coding, diy-guides, data-analysis" %}
  </div>
</div>

{% include search-info.html %}

{% include list.html data="posts" component="post-excerpt" filter="categories.nil? || !categories.include?('news')" %}
