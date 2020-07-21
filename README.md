readme.md meow meow

{% for sitepage in site.pages %}
meow
[{{sitepage.title | default: sitepage.url}}]({{ sitepage.url | remove_first: "/" }})
{% endfor %}
