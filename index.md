---
layout: default
---

<ul class="nav-menu">
{% for nav in site.data.nav %}
<li{% if nav.url == page.url %} class="active"{% endif %}><a href="{{ nav.url }}">{{ nav.text }}</a></li>
{% endfor %}</ul>

<div class="intro">
Thank you for visiting my personal page.

Quite often when I use a new app or technology I find that the concept is great, the underlying technology performs well, but the user experience (UX) is sub-par. 

Then I start thinking about how to make it better.

I'm that guy, none of the details are trivial.

Call it a curse, call it a superpower, but when you are called to defend UX principles, you have to answer the call.

By empathising with users of tech, we defenders employ our knowledge and methods to eliminate app-killing pitfalls and turn them into pure delight.
</div>