---
title: "Updates and information on wildfires"
layout: page 
sidebar: sidebars/2020-fire.html
active: true
incident:
  color: "#32cd32" # Change to #e02e02 for red
  name: "August 2020 wildfires"
description: "UC Santa Cruz continues to closely track the fires in Santa Cruz, Santa Clara, and neighboring counties. This event has resulted in multiple evacuations and air quality concerns."
---

<section style="border: 4px solid {{ page.incident.color }}; padding: 0; margin: 0 0 2em 0;">
  
  <h2 style="margin: 0 0 .5em 0; background-color: {{ page.incident.color }}; line-height: 1; padding: .5em .5em .45em .5em; color: white;"><i class="far fa-bell"></i> Campus status</h2>

  <div style="padding: .05em 2em .5em 2em;">

### Latest information

<b>{{ site.time | date: "%l:%M %P, %A, %b %d, %Y" }}</b>

As of Friday morning, the fire is about a mile north of upper campus. There is no fire activity on campus or in the City of Santa Cruz, and we hope that all the campus actions have been taken in an abundance of caution.

This morning’s news reports indicate that approximately 50,000 acres have burned so far and the fire is 0% contained. The fire continues to advance, and much of what will happen next depends on weather conditions such as wind direction and speed. UC Santa Cruz will continue to provide updates and information about the campus on this page. 

The residential campus has been completely evacuated, following a [Declaration of Emergency by Chancellor Cynthia Larive](https://news.ucsc.edu/2020/08/chancellor-declaration.html) and a subsequent [evacuation order](https://news.ucsc.edu/2020/08/images/calfire-order.pdf) from CalFire.

**An evacuation center for UC Santa Cruz students and employees living on campus** is in the Cocoanut Grove at the Boardwalk (use entrance B), 400 Beach Street, Santa Cruz. Parking is in the lot adjacent to the Coconut Grove. 

**Evacuation centers for the broader Santa Cruz community are open** at Santa Cruz County Fairground, 2601 E. Lake Avenue in Watsonville, and Santa Cruz Civic Auditorium, 307 Church Street, Santa Cruz.  

People will not be allowed to enter UC Santa Cruz residential campus because of the mandatory evacuation. Access to the residential campus will be limited to first responders and those authorized by UCSC Chief of Police Nader Oweis or his designee.

Any person who enters the residential campus, a closed off area or remains in the area after being ordered to evacuate may be found guilty of a criminal offense. Only use 911 for true emergencies. 

This continues to be a rapidly changing situation, and we encourage everyone to stay safe and informed. We ask each of you to monitor conditions that impact you locally as each of your situations will differ.

- Cal Fire is providing updates through its [Twitter account](https://twitter.com/CALFIRECZU)  and residents can sign up to [receive its email updates.](https://tinyurl.com/czulightning)
- CHP is [sharing information about road closures.](https://twitter.com/CHPscrz)
- Santa Cruz and San Mateo counties have a [real-time evacuation map](https://www.smco.community.zonehaven.com/).

### Campus updates

{% for m in site.data.messages %}
#### {{ m[0] | date: "%A, %b %d" }}
  {% for l in m[1] %}
  - [{{ l.title }}]({{ l.url }})
  {% endfor %}
{% endfor %}

</div>

</section>

<h2>General information</h2>
<ul>
<li><a href="https://www.smco.community.zonehaven.com">Evacuation map</a></li>
<li><a href="https://www.redcross.org/get-help/how-to-prepare-for-emergencies/types-of-emergencies/wildfire.html">Red Cross Wildfire Safety</a></li>
<li><a href="https://twitter.com/CALFIRECZU">CalFire Twitter account</a></li>
<li><a href="https://twitter.com/sccounty">Santa Cruz County Twitter account</a></li>
</ul>
<h2>Campus resources</h2>
<ul>
<li><a href="https://healthcenter.ucsc.edu">Student Health Center</a></li>
<li><a href="https://caps.ucsc.edu">Counseling and Psychological Services</a></li>
<li><a href="https://shr.ucsc.edu/benefits/eap/">Employee Assistance Program</a></li>
</ul>
