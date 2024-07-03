News
====
{% for p in site.news %}
- [{{ p.date }})]
    {{ p.content }}
{% endfor %}

