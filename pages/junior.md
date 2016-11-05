---
layout: page
show_meta: false
title: "Le coin des juniors"
header:
  image_fullwidth: header_pdb.jpg
  title: Centre D'études Napoléoniennes
permalink: "/junior/"
---
<ul>
    {% for post in site.categories.junior %}
    <li><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>