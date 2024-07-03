News
====
{% for p in site.news %}
- [{{ p.title }})]
    {{ p.content }}
{% endfor %}

