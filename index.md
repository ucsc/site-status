---
title: "Current active incidents"
layout: page
---

{% assign active_incidents = site.posts | where: "active", true %}
{% for p in active_incidents %}
  <h2><a href="{% if p.incident.link %}{{ p.incident.link }}{% else %}{{ p.url }}{% endif %}">{{ p.incident.name }}</a></h2>
  <p>{{ p.incident.description }}</p>
{% endfor %}

****

You can also check for campus status updates on our [Twitter]({{ site.social.twitter }}), [Facebook]({{ site.social.facebook }}), and [Instagram]({{ site.social.instagram }}) accounts.