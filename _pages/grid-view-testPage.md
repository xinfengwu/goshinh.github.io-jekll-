---
layout: archive
title: "grid-view-testPage"
permalink: /gridview/
author_profile: true
sidebar:
  nav: "courses"
---
This is a couses page.
<div class="grid__wrapper">
  {% for post in site.testcollections %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>
