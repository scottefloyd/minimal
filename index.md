---
layout: default
---

<ul class="nav-menu">
{% for nav in site.data.nav %}
<li{% if nav.url == page.url %} class="active"{% endif %}><a href="{{ nav.url }}">{{ nav.text }}</a></li>
{% endfor %}</ul>

<div class="intro">

<p>Thank you for visiting my personal page.</p>

<p>Quite often when I use a new app or technology I find that the concept is great, the underlying technology performs well, but the user experience (UX) is sub-par.</p>

<p>Then I start thinking about how to make it better.</p>

<p>I'm that guy, none of the details are trivial.</p>

<p>Call it a curse, call it a superpower, but when you are called to defend UX principles, you have to answer the call.</p>

<p>By empathising with users of tech, we defenders employ our knowledge and methods to eliminate app-killing pitfalls and turn them into pure delight.</p>

</div>