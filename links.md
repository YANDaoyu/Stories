---
layout: page
title: 友链
permalink: links.html
image: /public/images/links.jpg
order: 4
---

> God made relatives. Thank God we can choose our friends.

<ul class="links">
{% for item in site.links %}
<li>
    <p>
        <a href="{{ item.url }}" target="_blank" title="{{ site.title }}">
        {{ item.title }}
        </a>
    </p>
</li>
{% endfor %}
</ul>

这里暂时应该还没有人。