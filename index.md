---
title: "Active incidents"
layout: page
---

<p>Site updated: {{ site.time | date: "%l:%M %P, %A, %b %d, %Y" }}</p>

{% assign active_incidents = site.incidents | where: "active", true %}
{% for p in active_incidents %}
  
  <h2><a href="{% if p.link %}{{ p.link }}{% else %}{{ p.url }}{% endif %}">{{ p.title }}</a></h2>
  
  {{ p.excerpt }}

{% endfor %}

****

You can also check for campus status updates on our [Twitter]({{ site.social.twitter }}), [Facebook]({{ site.social.facebook }}), and [Instagram]({{ site.social.instagram }}) accounts.
<!-- Hi Rob! -->
