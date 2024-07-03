News
====
{% for p in site.news %}
- [{{ p.date | date: "%m-%d %H:%M:%S" }}]
    {{ p.content }}
{% endfor %}

