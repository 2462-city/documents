---
title: Gazdasági bizottság jegyzőkönyvei
---

{% assign files = site.static_files | where: "gazdasagi-bizottsag-jegyzokonyvei", true %}
<ul>
{% for file in files %}
  <li>
   <a href="{{ site.basepath }}{{ file.path }}">{{ file.basename }}</a>
  </li>
{% endfor %}
</ul>
