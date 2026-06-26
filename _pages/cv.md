---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.S. candidate, School of Physics, Peking University

Research Interests
======
* Physics
* Astrophysics and related computational methods
* Scientific programming and data analysis

Publications
======
{% if site.publications.size > 0 %}
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
{% else %}
No publications are listed yet.
{% endif %}

Skills
======
* Python
* LaTeX
* Scientific computing
* Data analysis
