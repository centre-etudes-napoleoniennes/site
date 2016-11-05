---
layout: page
show_meta: false
title: "Les activités"
header:
  image_fullwidth: header_pdb.jpg
  title: Centre D'études Napoléoniennes
permalink: "/activites/"
---
<ul>
    {% for post in site.categories.activites %}
    <li><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>