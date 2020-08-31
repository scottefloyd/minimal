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

<a href="https://kristyliebetreuphotography.com/" target="_blank">
![Kristy Liebetreu Photography]({{ site.baseurl }}/assets/img/kristy.png "screen shot of photography website")
</a>


### Conquest Home Builders
<a href="http://royscorner.com/wp/" target="_blank">
![Conquest Home builders]({{ site.baseurl }}/assets/img/conquest.png "screenshot of homebuilder website")
</a>


### Roy's Hardware
<a href="http://conquestbuilders.com/" target="_blank">
![Roy's Hardware]({{ site.baseurl }}/assets/img/roys.png "screenshot of hardware store website")
</a>