---
layout: archive
title: "所教课程"
permalink: /courses/
author_profile: true
sidebar:
  nav: "courses"
---
This is a couses page.

<ul>
  {% for item in site.testcollections %}
  <ul>
    <a href="{{ item.url | prepend: item.baseurl }}">{{ item.title }}</a>
  </ul>
  {% endfor %}
  {% for item in site.clanguge_for_pupils %}
  <ul>
    <a href="{{ item.url | prepend: item.baseurl }}">{{ item.title }}</a>
   </ul> 
  {% endfor %}
  {% for item in site.CLangugeSoEasy %}
  <ul>
    <a href="{{ item.url | prepend: item.baseurl }}">{{ item.title }}</a>
   </ul> 
  {% endfor %}
</ul>
