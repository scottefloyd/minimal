---
layout: web-portfolio
permalink: /web-portfolio/
---

<ul class="nav-menu">
{% for nav in site.data.nav %}
<li{% if nav.url == page.url %} class="active"{% endif %}><a href="{{ nav.url }}">{{ nav.text }}</a></li>
{% endfor %}</ul>