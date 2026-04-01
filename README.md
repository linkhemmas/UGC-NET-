# Welcome to UGC-NET Previous Papers
This list updates automatically whenever I add a new file to my folders!

## All Available Papers:

<ul>
{% for page in site.pages %}
  {% if page.name != 'README.md' and page.name != 'index.md' %}
    <li>
      <a href="{{ page.url | relative_url }}">{{ page.path }}</a>
    </li>
  {% endif %}
{% endfor %}
</ul>
