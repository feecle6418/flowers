# 鲜花冷柜

不仅冷藏，还冷冻。

<ul>
{% assign sorted_pages = site.pages | sort: "title" | reverse %}
{% for page in sorted_pages %}
  {% if page.category == "post" %}
    <li><a href="{{ page.url }}">{{ page.title }}</a></li>
  {% endif %}
{% endfor %}
</ul>
 
 
 
