News
====
{% for p in site.news % | sort_natural: "date"}
- {{ p.date | date: "%y-%m-%d" }}
    {{ p.content }}
{% endfor %}

