---
layout: page
title:  "Seznam poslanců"
---

<ul>
{% for poslanec in site.data.poslanci %}
  <li><a class="page-link" href="{{ poslanec.jmeno | datapage_url: '/li/poslanci' }}">{{ poslanec.jmeno }}</a></li>
{% endfor %}
</ul>

<!-- | datapage_url: "/li/poslanci" -->
