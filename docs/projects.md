---
layout: page
title: Projects
permalink: /projects/
nav_header: true
---

<div class="container mx-auto px-2 py-4">
    {% for post in site.posts %}
        {% include post_block.html %}
    {% endfor %}
</div>