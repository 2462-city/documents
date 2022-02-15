### Képviselőtestületi jegyzőkönyvek

#### 2021

{% assign kt_2021_files = site.static_files | where: "kepviselo-testuleti-jegyzokonyvek-2021", true %}
{% for pdf in kt_2021_files %}
* [ {{ pdf.basename}} ] ({{ pdf.path }})
{% endfor %}

