---
title: "Incidents"
layout: page
---

<!-- <p>Site updated: {{ site.time | date: "%l:%M %P, %A, %b %d, %Y" }}</p> -->

For website or web services outages, [check the ITS incidents page](http://slughub.ucsc.edu/its).

{% assign active_incidents = site.incidents | where: "active", true %}
{% for p in active_incidents %}
  
  <h2><a href="{% if p.link %}{{ p.link }}{% else %}{{ p.url }}{% endif %}">{{ p.title }}</a></h2>
  
  {{ p.excerpt }}

{% else %}

There are currently no major incidents or emergencies at UC Santa Cruz. In the event of an emergency, [ucsc.edu/status](http://www.ucsc.edu/status/) will be updated if there is important information to share with the campus community.

{% endfor %}

****

You can also check for updates on our [Instagram]({{ site.social.instagram }}) account.
