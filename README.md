readme.md meow meow

{% for sitepage in page_list %}
meow
[{{sitepage.title | default: sitepage.url}}]({{ sitepage.url | remove_first: "/" }})
{% endfor %}
