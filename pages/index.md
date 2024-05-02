---
title: IUB Organizing Hub
layout: homepage
permalink: /
---

# News & Updates

## Whitten/Shrivastav Invite Snipers and State Troopers To Campus

A long-standing policy on protest guidelines was changed in a closed-door meeting on April 24, less than 24 hours before the start of a scheduled protest. The policy change was used to justify the presence of state police on IU Bloomington's campus and the arrest of more than 50 students and faculty on April 25 and 27. Year-long bans were meted out to those arrested. [Read more...](content/policepresence.html)

# Vote of No Confidence

An April 16 all-faculty meeting resulted in votes of no confidence for 3 high-level IU administrators. [View no-confidence news](content/VoNC.html) and read the timeline of grievances below.

## Timeline of Grievances


<div class="grid-container">
<div class="grid-x grid-padding-x grid-margin-x">

{% for grievance in site.data.grievances %}
{% unless grievance.homepagedisplay == "no" %}
<div class="cell filter-item small-12 medium-6 large-4 card">
<div class="card-thumbnail">
<a href="/content/{{ grievance.link }}" alt="{{grievance.title}}">
<img class="square thumbnail" src="{{grievance.image}}" alt="{{grievance.title}}"/></a>
</div>
<h3 class="card-title accentbg"><a href="/content/{{ grievance.link }}" alt="{{grievance.title}}">{{grievance.title}}</a></h3>
<h4 class="card-contributor">{{ grievance.date | date: "%b %Y" }}</h4>
<p class="card-desc">{{grievance.shortdesc}} (<a href="/content/{{grievance.link}}"  alt="{{grievance.title}}">read more...</a>)</p>
</div>
{% endunless %}
{% endfor %}


</div>
</div>