---
layout: web-portfolio
permalink: /web-portfolio/
---

<ul class="nav-menu">
{% for nav in site.data.nav %}
<li{% if nav.url == page.url %} class="active"{% endif %}><a href="{{ nav.url }}">{{ nav.text }}</a></li>
{% endfor %}</ul>

## WEB PORTFOLIO

### Kristy Liebetreu Photography

<a href="https://kristyliebetreuphotography.com/">
![Kristy Liebetreu Photography]({{ site.baseurl }}/assets/img/kristy.png "screen shot of photography website")
</a>

### Conquest Home Builders

![Conquest Home builders]({{ site.baseurl }}/assets/img/conquest.png "screenshot of homebuilder website")

### Roy's Hardware

![Roy's Hardware]({{ site.baseurl }}/assets/img/roys.png "screenshot of hardware store website")