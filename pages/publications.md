---
layout: page
show_meta: false
title: "Les publications"
header:
  image_fullwidth: header_pdb.jpg
  title: Centre D'études Napoléoniennes
permalink: "/publications/"
---
<ul>
    {% for post in site.categories.publications %}
    <li><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
