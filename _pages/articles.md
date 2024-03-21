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
Link current articles here.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.articles reversed %}
  {% include archive-single.html %}
{% endfor %}

---

Ideas
======
* Esoteric need/motivation for answering the question what makes a church a church.
  * Include thorny missiological questions as motivations.
* Establish a rubric for church.
* Apply rubric to missiological questions.
