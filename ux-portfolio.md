---
layout: ux-portfolio
permalink: /ux-portfolio/
---

{:.nav-menu}
{% for nav in site.data.nav %}
<li{% if nav.url == page.url %} class="active"{% endif %}><a href="{{ nav.url }}">{{ nav.text }}</a></li>
{% endfor %}

Break

<ul class="nav-menu">
{% for nav in site.data.nav %}
<li{% if nav.url == page.url %} class="active"{% endif %}><a href="{{ nav.url }}">{{ nav.text }}</a></li>
{% endfor %}</ul>

Break

<li>{{ page.url }}</li>

{:.nav-menu}
[UX PORTFOLIO](../ux-portfolio)   [RESUME/CV](../online-cv)   [WEB DESIGN](../web-portfolio)