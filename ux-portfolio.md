---
layout: ux-portfolio
permalink: /ux-portfolio/
---

{:.nav-menu}
{% for nav in site.data.nav %}
<li{% if nav.url == page.url %} class="active"{% endif %}><a href="{{ nav.url }}">{{ nav.text }}</a></li>
{% endfor %}

Break

{:.nav-menu}
{% for nav in site.data.nav %}
{% if nav.url == page.url %} {:.active}{% endif %}
[nav.text](nav.url)
{% endfor %}

Break

<li>{{ page.url }}</li>

{:.nav-menu}
[UX PORTFOLIO](../ux-portfolio)   [RESUME/CV](../online-cv)   [WEB DESIGN](../web-portfolio)