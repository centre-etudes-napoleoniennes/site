---
layout: page
show_meta: false
title: "Partenaires et mécènes"
header:
  image_fullwidth: header_pdb.jpg
  title: Centre D'études Napoléoniennes
permalink: "/partenaires/"
---
<ul>
    {% for post in site.categories.partenaires %}
    <li><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>