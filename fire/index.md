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

Cal Fire lifted its emergency evacuation order for the UC Santa Cruz residential campus at 6 p.m. on Wednesday. 

Chancellor Larive has amended the Aug. 20 emergency declaration so that employees who live at Laureate Court, Hagar Court, Ranch View Terrace, Hagar Meadow, and Cardiff Terrace can return to their homes tonight. The rest of the residential campus remains closed, as do the Coastal Science Campus and Westside Research Park. [Read more](https://news.ucsc.edu/2020/08/reopening-employee-housing.html).
                                                        
**Except for the people living in the employee housing communities outlined above, no one should attempt to access the residential campus, Coastal Science Campus, or Westside Research Park until directed that it is OK to do so.**

As of Wednesday, the fire remains about a mile north of upper campus. Cal Fire crews have established fire lines to try and slow the spread toward the campus and the city of Santa Cruz. Conditions can change quickly, and we continue to monitor the situation closely.

There are approximately 80,100 acres involved, 538 structures have been destroyed, and the fire is now at 19% containment, according to [Cal Fire’s Wednesday morning update](https://files.constantcontact.com/13ae4c7f701/c331c72d-edd3-492f-9648-2be933b8631e.pdf).

There is no fire activity on campus or in the City of Santa Cruz, and we hope that all the campus actions have been taken in an abundance of caution.

### Get help

UC Santa Cruz has an array of support services for [employees](https://news.ucsc.edu/2020/08/support-services-for-employees-impacted-by-wildfires.html)  and [students](https://news.ucsc.edu/2020/08/you-are-not-alone.html) affected by the wildfires. 

**An evacuation center for UC Santa Cruz students and employees living on campus** is in the Cocoanut Grove at the Boardwalk (use entrance B), 400 Beach Street, Santa Cruz. Parking is in the lot adjacent to the Cocoanut Grove. 

**Evacuation centers for the broader Santa Cruz community are open** at the following locations:

- Santa Cruz County Fairground, 2601 E. Lake Avenue in Watsonville
- Santa Cruz Civic Auditorium, 307 Church Street, Santa Cruz (AT CAPACITY) Seventh Day Adventist Camp Grounds, 1931 Soquel San Jose Rd (AT CAPACITY)
- Cabrillo College, 6500 Soquel Drive, Aptos CA
- Santa Cruz Bible Church, 440 Frederick Street, Santa Cruz
- Simpkins Family Swim Center, 919 17th Ave (ADA only)
- Twin Lakes Church, 2701 Cabrillo College Drive

### Campus evacuated, do not try to enter

The residential campus has been completely evacuated, following a [Declaration of Emergency by Chancellor Cynthia Larive](https://news.ucsc.edu/2020/08/chancellor-declaration.html) and a subsequent [evacuation order](https://news.ucsc.edu/2020/08/images/calfire-order.pdf) from CalFire. 

People will not be allowed to enter UC Santa Cruz residential campus because of the mandatory evacuation. Access to the residential campus will be limited to first responders and those authorized by UCSC Chief of Police Nader Oweis or his designee.

Any person who enters the residential campus, a closed off area or remains in the area after being ordered to evacuate may be found guilty of a criminal offense. Only use 911 for true emergencies. 

### Stay informed

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

## General information

- [Evacuation map](https://www.smco.community.zonehaven.com)
- [Red Cross Wildfire Safety](https://www.redcross.org/get-help/how-to-prepare-for-emergencies/types-of-emergencies/wildfire.html)
- [CalFire Twitter account](https://twitter.com/CALFIRECZU)
- [Santa Cruz County Twitter account](https://twitter.com/sccounty)

## Campus resources

- [Student Health Center](https://healthcenter.ucsc.edu)
- [Counseling and Psychological Services](https://caps.ucsc.edu)
- [Employee Assistance Program](https://shr.ucsc.edu/benefits/eap/)
