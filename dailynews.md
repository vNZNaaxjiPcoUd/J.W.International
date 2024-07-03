News
====

{% for p in site.news % | sort_natural: "date" | reverse %}
- {{ p.date | date: "%a, %b %d, %Y" }}
    {{ p.content }}
{% endfor %}

