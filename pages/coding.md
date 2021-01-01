---
layout: page
subheadline: "Getting Started with Coding"
title: "What is programming anyway?"
teaser: "If you're thinking about learning how to write code, make programs, or to dig deeper into your computer, here are some resources! For those of you interested in video games, we have a self-contained taste of programming that will get you introduced to some general concepts. If you're more interested in data analysis, data cleaning, and data organization, there is a Python-oriented set of notes that can help get you started."
header:
   image_fullwidth: "/images/coding_header.png"
permalink: "/coding/"
---
<ul>
    {% for post in site.tags.header %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
