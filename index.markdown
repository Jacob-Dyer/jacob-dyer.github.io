---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
title:  
---

{% for cat in site.category-list %}
### {{ cat }}
<ul>
  {% for page in site.pages %}
    {% if page.resource == true %}
      {% for pc in page.categories %}
        {% if pc == cat %}
          <li><a href="{{ page.url }}">{{ page.title }}</a></li>
        {% endif %}   <!-- cat-match-p -->
      {% endfor %}  <!-- page-category -->
    {% endif %}   <!-- resource-p -->
  {% endfor %}  <!-- page -->
</ul>
{% endfor %}  <!-- cat -->