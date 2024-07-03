News
====
{% for p in site.news % | sort "date"}
- [{{ p.date | date: "%m-%d %H:%M:%S" }}]
    {{ p.content }}
{% endfor %}

