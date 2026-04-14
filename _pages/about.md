---
permalink: /
title: "Lixian Chen"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi! I am **Lixian Chen**, an undergraduate student at **Guangdong University of Technology**.

My research interests include **Data Mining**, **Computer Vision**, and related topics in machine learning.

## About Me

I am currently focused on academic research and project work. This homepage collects my publications, research interests, and selected academic activities.

## Publications

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
