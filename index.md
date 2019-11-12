---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

Keine Kochrezepte:

{% for recipe in site.recipes %}
  * [{{ recipe.title }}]({{ recipe.url }})
{% endfor %}
