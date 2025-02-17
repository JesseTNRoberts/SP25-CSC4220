---
layout: page
title: Home / Schedule
nav_order: 1
description: A week-to-week description of the content covered in the course.
course:
currWeekNumber: 4
---

# CSC 4220: Data Mining and Machine Learning

{: .mb-2 }
Tennesse Tech, Spring 2025
{: .mb-0 .fs-6 .text-grey-dk-000 }

<!--
[Ed](https://edstem.org/us/courses/62812){:target="\_blank" .btn .btn-ed .mr-1 }
[Datahub](http://data100.datahub.berkeley.edu/){:target="\_blank" .btn .btn-datahub .mr-1 }
[Gradescope](https://www.gradescope.com/courses/827978){:target="\_blank" .btn .btn-gradescope .mr-1 }
[Lectures Playlist](https://www.youtube.com/playlist?list=PLQCcNQgUcDfqlx2UJTlv22jsPAu0Yg_kg){:target="\_blank" .btn .btn-youtube .mr-1}
[Additional Accommodations](https://forms.gle/HYbsLwhtSvmsCefX9){:target="\_blank" .btn .btn-blue .mr-1 }
[Office Hours Queue](https://oh.ds100.org/){:target="\_blank" .btn .btn-oh .mr-1} -->

<div>
{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
  <div class="role">
    {% for staffer in instructors %}
    {{ staffer }}
    {% endfor %}
  </div>
</div>

{: .highlight }

> Welcome to [Week {{page.currWeekNumber}}](#week-{{page.currWeekNumber}}) of CSC4220!

<!-- 
{: .note }
> <s pan style="color:red">**Homework 2 will be assigned on Wednesday**</span> 

{: .note }
> <span style="color:red">**Class will be in AIEB 130 from now on!**</span>  
<a name="schedule"></a> -->

## Schedule

{% for module in site.modules %}
{{ module }}
{% endfor %}
