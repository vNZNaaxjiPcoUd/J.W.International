News
====
{% for p in site.news % | sort_natural: "date"}
- [{{ p.date | date: "%m-%d %H:%M:%S" }}]
    {{ p.content }}
{% endfor %}

