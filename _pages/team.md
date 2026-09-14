---
title: "Team"
layout: gridlay
excerpt: "Team members"
sitemap: false
permalink: /team/
---

## Principal Investigator

<div class="row" style="margin-bottom: 40px;">
<div class="col-sm-12 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/ua.png" class="img-responsive" width="22%" style="float: left; margin-right: 25px; margin-bottom: 15px;" />
  <h4 style="margin-top: 0;">Usman Amjad, Ph.D. <small>(<a href="https://cct.neduet.edu.pk/sites/default/files/csit/CV_new/Usman25.pdf">Curriculum Vitae</a>)</small></h4>
  <i>Associate Professor</i><br>
  <i>Department of Computer Science and Information Technology (CSIT)</i><br>
  <a href="mailto:usmanamjad@neduet.edu.pk">usmanamjad@neduet.edu.pk</a>
  <p style="margin-top: 15px;">Dr. Usman Amjad is an Associate Professor in the Department of Computer Science and Information Technology at NED University of Engineering &amp; Technology, Karachi, and an HEC-approved PhD supervisor. His research interests include machine learning, deep learning, computer vision, nature-inspired computing, and medical image analysis, with a particular emphasis on brain imaging, disease characterization, and computational analysis of neurological and neuro-oncological diseases.</p>
  <p><b>Administrative &amp; departmental roles</b></p>
  <ul>
    <li>Class Advisor, BS Computer Science (BSCS)</li>
    <li>ORIC Coordinator, CSIT Department</li>
    <li>Internship Coordinator, CSIT Department</li>
    <li>Member, Final Year Design Project (FYDP) Steering Committee</li>
  </ul>
</div>
</div>

## Group Members

{% for member in site.data.team_members %}

<div class="row" style="margin-bottom: 25px;">
<div class="col-sm-12 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="15%" style="float: left; margin-right: 20px; margin-bottom: 10px;" />
  <h4 style="margin-top: 0;">{{ member.name }}</h4>
  <i>{{ member.info }}</i><br>
  <a href="mailto:{{ member.email }}">{{ member.email }}</a>
</div>
</div>

{% endfor %}