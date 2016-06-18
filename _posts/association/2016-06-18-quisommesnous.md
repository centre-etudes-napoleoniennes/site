---
layout: page
subheadline:  "L'association"
title:  "Qui sommes-nous ?"
teaser: "Association loi de 1901 créée en 1966, le Centre d'Études Napoléoniennes (CEN) a pour mission de favoriser l’approfondissement de la connaissance historique relative à la révolution, au 1er et au 2d empire à partir de recherches et de documents nouveaux ou inédits. 
         Libre et indépendant sur le plan intellectuel et financier, le CEN publie les résultats de ses travaux historiques dans la revue Études Napoléoniennes et dans des ouvrages particuliers. Le CEN collabore avec des chercheurs et universitaires français et étrangers."
categories:
    - association
tags:
    - post format
image:
   thumb: "gallery-example-1-thumb.jpg"
gallery:
    - image_url: gallery-example-1.jpg
      caption: Great images by Unsplash.com
    - image_url: gallery-example-2.jpg
      caption: Great images by Unsplash.com
    - image_url: gallery-example-3.jpg
      caption: Great images by Unsplash.com
    - image_url: gallery-example-4.jpg
      caption: Great images by Unsplash.com
    - image_url: gallery-example-5.jpg
      caption: Great images by Unsplash.com
    - image_url: gallery-example-6.jpg
      caption: Great images by Unsplash.com
    - image_url: gallery-example-7.jpg
      caption: Great images by Unsplash.com
    - image_url: gallery-example-8.jpg
      caption: Great images by Unsplash.com
---
You just need to choose a template like the [`page`][3]- or [`page-fullwidth`][4]-template and then just use `{% raw %}{% include gallery %}{% endraw %}`.
<!--more-->

{% include gallery %}


~~~
gallery:
    - image_url: gallery-image.jpg
~~~

If you like captions, give each image a caption:

~~~
gallery:
    - image_url: gallery-image.jpg
       caption: Starting Page with huge One Logo
~~~

## Other Post Formats
{: .t60 }
{% include list-posts tag='post format' %}



 [1]: http://foundation.zurb.com/docs/components/clearing.html
 [2]: http://foundation.zurb.com/docs/components/block_grid.html
 [3]: {{ site.url }}/design/page/
 [4]: {{ site.url }}/design/page-fullwidth/
