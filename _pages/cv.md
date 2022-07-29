---
layout: archive
#title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* [2019-2022] PhD in Data Science, University of Edinburgh, UK
* [2018-2019] MSc(R) Data Science, University of Edinburgh, UK
* [2014-2018] BSc Hons Mathematics, University of Edinburgh, UK

Awards
======
* [2018-2022] EPSRC Ph.D funding
* [2014-2018] MyBrainSc Scholarship

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  

