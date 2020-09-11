---
title: "Updates and information on wildfires"
layout: page 
sidebar: sidebars/2020-fire.html
active: true
incident:
  color: "#fdc700" # Change to #e02e02 for red
  name: "August 2020 wildfires"
description: "UC Santa Cruz continues to closely track the fires in Santa Cruz, Santa Clara, and neighboring counties. This event has resulted in multiple evacuations and air quality concerns."
---

<section style="border: 4px solid {{ page.incident.color }}; padding: 0; margin: 0 0 2em 0;">
  
  <h2 style="margin: 0 0 .5em 0; background-color: {{ page.incident.color }}; line-height: 1; padding: .5em .5em .45em .5em; color: white;"><i class="far fa-bell"></i> Campus status</h2>

  <div style="padding: .05em 2em .5em 2em;">

### Latest information

<b>{{ site.time | date: "%l:%M %P, %A, %b %d, %Y" }}</b>

Effective immediately all facilities on the residential campus can resume their pre-evacuation status. The only activities that may resume are those that had been approved prior to the Aug. 20 evacuation through the [COVID-19 resumption approval process](https://recovery.ucsc.edu/). Smoke odors may still be present and air scrubbers may still be running in the hallways. Should your department need assistance with mitigating the smoke odor, please contact Environmental Health and Safety (EH&S) at ehs@ucsc.edu.

Information specific to student on-campus housing will be sent by the housing office directly to students. 

As fires continue to burn throughout the region, the campus continues to track air quality, and will utilize the [UC guidance for addressing air quality](https://drive.google.com/file/d/1ZHxoXZL-NuR6SAZjkrHSP3ISewrkXGbF/view) to inform any subsequent actions we need to take. 

Please be mindful that due to the wildfire event and campus closure, the wildlife population on campus has increased. It's especially important to go slow on campus roadways and be aware when out on campus trails. In addition to the turkeys and deer, we have seen an increase in the coyote, fox and other species throughout the campus.

### Get help

UC Santa Cruz has an array of support services for [employees](https://news.ucsc.edu/2020/08/support-services-for-employees-impacted-by-wildfires.html) and [students](https://news.ucsc.edu/2020/08/you-are-not-alone.html) affected by the wildfires. 


### Stay informed

We encourage everyone to stay safe and informed. We ask each of you to monitor conditions that impact you locally as each of your situations will differ.

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

## General information

- [Evacuation map](https://www.smco.community.zonehaven.com)
- [Red Cross Wildfire Safety](https://www.redcross.org/get-help/how-to-prepare-for-emergencies/types-of-emergencies/wildfire.html)
- [CalFire Twitter account](https://twitter.com/CALFIRECZU)
- [Santa Cruz County Twitter account](https://twitter.com/sccounty)

## Campus resources

- [Student Health Center](https://healthcenter.ucsc.edu)
- [Counseling and Psychological Services](https://caps.ucsc.edu)
- [Employee Assistance Program](https://shr.ucsc.edu/benefits/eap/)
