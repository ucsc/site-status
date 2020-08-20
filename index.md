---
title: "Current active incidents"
layout: page
---

{% assign active_incidents = site.pages | where: "active", true %}
{% for p in active_incidents %}
  <h2><a href="{{ p.url }}">{{ p.incident.name }}</a></h2>
  <p>{{ p.description }}</p>
{% endfor %}

****

You can also check for campus status updates on our [Twitter]({{ site.social.twitter }}), [Facebook]({{ site.social.facebook }}), and [Instagram]({{ site.social.instagram }}) accounts.
