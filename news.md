News
====
{% for p in site.news %}
-[{{ p.url }}]({{ p.title }})
    {{ p.excerpt }}
{% endfor %}

