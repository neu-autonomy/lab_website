---
title: "Autonomy & Intelligence Lab at Northeastern University - Team"
layout: gridlay
excerpt: "Autonomy & Intelligence Lab at Northeastern University - Team"
sitemap: false
permalink: /team/
---

# Group Members

**We are looking to hire a talented postdoctoral researcher. Please see [this page]({{ site.url }}{{ site.baseurl }}/joinus) for info about how to apply!**

<!-- **We are planning to hire multiple PhD students in the 2022-2023 cycle -- please consider applying to ECE or Khoury at Northeastern!** -->

<!-- Jump to [staff](#staff), [master and bachelor students](#master-and-bachelor-students), [alumni](#alumni), [administrative support](#administrative-support), [lab visitors](#lab-visitors). -->

## Faculty
{% assign number_printed = 0 %}
{% for member in site.data.team_members %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/members/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }}</i>
  <h4><a href="http://mfe7.github.io" target="_blank">Personal Webpage</a></h4>

  <ul style="overflow: hidden">

  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  {% if member.number_educ == 5 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  <li> {{ member.education5 }} </li>
  {% endif %}

  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

## Postdoctoral Researchers
{% assign number_printed = 0 %}
{% for member in site.data.postdocs %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
{% if member.photo %}
<img src="{{ site.url }}{{ site.baseurl }}/images/members/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
{% endif %}
<h4>{{ member.name }}</h4>

{% if member.personal_webpage %}
<h5><a href="{{member.personal_webpage}}" target="_blank">Personal Webpage</a></h5>
{% endif %}

{% if member.research_interests %}
<h5>Research Interests: {{member.research_interests}}</h5>
{% endif %}
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}


## PhD Students
{% assign number_printed = 0 %}
{% for member in site.data.students %}
  
{% if member.degree == "phd" %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
{% if member.photo %}
<img src="{{ site.url }}{{ site.baseurl }}/images/members/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
{% endif %}

<h4>{{ member.name }}</h4>

{% if member.personal_webpage %}
<h5><a href="{{member.personal_webpage}}" target="_blank">Personal Webpage</a></h5>
{% endif %}

{% if member.research_interests %}
<h5>Research Interests: {{member.research_interests}}</h5>
{% endif %}

</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}


## MS Students
{% assign number_printed = 0 %}
{% for member in site.data.students %}
  
{% if member.degree == "ms" %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
{% if member.photo %}
<img src="{{ site.url }}{{ site.baseurl }}/images/members/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
{% endif %}

<h4>{{ member.name }}</h4>

{% if member.personal_webpage %}
<h5><a href="{{member.personal_webpage}}" target="_blank">Personal Webpage</a></h5>
{% endif %}

{% if member.research_interests %}
<h5>Research Interests: {{member.research_interests}}</h5>
{% endif %}

</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}


## Undergraduate Students
{% assign number_printed = 0 %}
{% for member in site.data.students %}
  
{% if member.degree == "bs" %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
{% if member.photo %}
<img src="{{ site.url }}{{ site.baseurl }}/images/members/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
{% endif %}

<h4>{{ member.name }}</h4>

{% if member.personal_webpage %}
<h5><a href="{{member.personal_webpage}}" target="_blank">Personal Webpage</a></h5>
{% endif %}

{% if member.research_interests %}
<h5>Research Interests: {{member.research_interests}}</h5>
{% endif %}

</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}


