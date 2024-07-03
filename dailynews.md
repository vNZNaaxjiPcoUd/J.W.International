News
====
{% assign pp = site.news | sort_natural: "date" | reverse %}
{% for p in pp %}
- {{ p.date | date: "%a, %b %d, %Y" }}
    {{ p.content }}
{% endfor %}

