## Welcome to 2462.city document repository

### Képviselőtestületi jegyzőkönyvek

[kepviselo-testuleti-jegyzokonyvek-2021](/kepviselo-testuleti-jegyzokonyvek-2021)

{% assign image_files = site.static_files | where: "kepviselo-testuleti-jegyzokonyvek-2021", true %}
{% for myimage in image_files %}
  {{ myimage.path }}
{% endfor %}

