---
permalink: /learning-jekyll/
layout: post
title: "Learning Jekyll"
date: 2021-03-01 00:59:03 +0545
categories: jekyll learning
author: dave
---

Learning Jekyll

<!-- {% for member in site.data.members %}
{{ member.name }}
{% endfor %} -->

{% assign author = site.data.people[page.author] %}
<a rel="author"
  href="https://twitter.com/{{ author.twitter }}"
  title="{{ author.name }}">
    {{ author.name }}
</a>