---
layout: archive
title: "Articles"
permalink: /articles/
author_profile: true
redirect_from:
  - /articles
---

{% include base_path %}

---

<details closed markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details>

---

Articles
======
* B.S. in Polymer Color Chemistry
   * NC State University, 2018
   * Cumulative GPA: 3.90/4.0
* M.Div. in Missiology
   * Southeastern Baptist Theological Seminary, 2025 (expected)
   * Cumulative GPA: 4.0/4.0

Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Papers
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
  
