---
layout: page
title: Staff
nav_order: 7
description: A listing of all the course staff members.
---


**Note:** Consult the [calendar]({{ site.baseurl }}/calendar) for the most up-to-date office hours. All GSI Office Hours will be held in Warren 101B.

<a name = 'inst'></a>

## Teaching Team

<div class="role">
  {% assign instructors = site.staffers | where: 'role', 'Instructor' %}
  {% for staffer in instructors %}
  {{ staffer }}
  {% endfor %}
</div>

<!--
<a name = 'leads'></a>

## Leads

<div class="role">
  {% assign head_teaching_assistants = site.staffers | where: 'team', 'Head TA' %}
  {% for staffer in head_teaching_assistants %}
    {{ staffer }}
  {% endfor %}
  {% assign lead_teaching_assistants = site.staffers | where: 'role', 'Lead Teaching Assistant' %}
  {% for staffer in lead_teaching_assistants %}
    {% if staffer.team != 'Head TA' %}
      {{ staffer }}
    {% endif %}
  {% endfor %}
  {% assign lead_teaching_assistants = site.staffers | where: 'role', 'Lead Teaching Assistant 12' %}
  {% for staffer in lead_teaching_assistants %}
    {% if staffer.team != 'Head TA' %}
      {{ staffer }}
    {% endif %}
  {% endfor %}
</div>

<a name = 'ucs2s'></a>

## UCS2s

<div class="role">
  {% assign ucs2s = site.staffers | where: 'role', 'UCS2 12' %}
  {% for staffer in ucs2s %}
    {{ staffer }}
  {% endfor %}
  {% assign ucs2s = site.staffers | where: 'role', 'UCS2' %}
  {% for staffer in ucs2s %}
    {{ staffer }}
  {% endfor %}
</div>

<a name = 'ucs1s'></a>

## UCS1s

<div class="role">
  {% assign ucs1s = site.staffers | where: 'role', 'UCS1' %}
  {% for staffer in ucs1s %}
    {{ staffer }}
  {% endfor %}
</div> -->

<!---
<a name = 'tutors'></a>

## Tutors

<div class="role">
  {% assign readers = site.staffers | where: 'role', 'Tutor' %}
  {% for staffer in readers %}
  {{ staffer }}
  {% endfor %}
</div>

-->


<!-- <a name = 'readers'></a>

## Readers

<div class="role">
  {% assign readers = site.staffers | where: 'role', 'Reader' %}
  {% for staffer in readers %}
  {{ staffer }}
  {% endfor %}
</div> -->
