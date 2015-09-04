---
layout: page
subheadline: "Projekte"
title: "Alle Projekte!"
teaser: "Teaser.."
header:
   image_fullwidth: "header_unsplash_5.jpg"
permalink: "/projects/"
---
<ul>
    {% for post in site.tags.header %}
    <li><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
