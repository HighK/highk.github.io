---
layout: page
---
<ul id="post-list">
    {% for post in site.categories.test %}
        {% include item.html %}
    {% endfor %}
</ul>
{% include pagination.html %}
