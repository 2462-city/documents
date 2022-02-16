### Képviselőtestületi jegyzőkönyvek

#### 2021

{% assign kt_2021_files = site.static_files | where: "kepviselo-testuleti-jegyzokonyvek-2021", true %}
<ul>
{% for pdf in kt_2021_files %}
  <li>
   <a href="{{ site.basepath }}{{ pdf.path }}">{{ pdf.basename }}</a>
  </li>
{% endfor %}
</ul>
