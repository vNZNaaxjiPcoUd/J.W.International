News
====

{% for p in site.news % | sort_natural: "date" %}
- {{ p.date | date: "%a, %b %d, %Y" }}
    {{ p.content }}
{% endfor %}

