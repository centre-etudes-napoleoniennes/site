---
layout: page
show_meta: false
title: "Agenda - Newsletter"
header:
  image_fullwidth: header_pdb.jpg
  title: Centre D'études Napoléoniennes
permalink: "/agenda/"
---
<ul>
    {% for post in site.categories.agenda %}
    <li><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>