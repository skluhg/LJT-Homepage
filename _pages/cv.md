---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education

* PhD in Computer Science, Hong Kong University of Science and Technology, 2024 - present
* BEng, Shanghai Jiao Tong University, 2020 - 2024

## Work experience

* Research Intern, MINIMAX, February 2025 - present
* Research Intern, Tencent WXG, June 2024 - September 2024 (supervisor: Zifei Shan)
* Research Intern, Shanghai AI Lab, June 2023 - December 2023 (supervisor: Prof. Yu Cheng)

## Publications

  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

## Talks

  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
## Teaching

  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
