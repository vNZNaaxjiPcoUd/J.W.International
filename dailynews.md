## News

{% assign pp = site.news | sort_natural: "date" | reverse %}
{% for p in pp %}
<div class="w3-card w3-grey">
### {{ p.date | date: "%a, %b %d, %Y" }}

{{ p.content }}
  <br><br>
</div>
{% endfor %}

