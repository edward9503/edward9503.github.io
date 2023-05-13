---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

#### TEST
<table>
<colgroup>
  <col width="20%" />
  <col width="80%" />
</colgroup>
<tbody>
<tr>
  <td markdown="span"> [<img src="/images/research/epr.png" align="right" alt="Drawing" style="height: 70px; margin:0px 10px"/>](https://www.youtube.com/watch?v=TODO)</td>
  <td markdown="span">[Passive Whole-body Control for Quadruped Robots: Experimental Validation over Challenging Terrain](/publications/2021-robotinmirror.html).
  S. Fahmi<sup>&#x2020;</sup>, **C. Mastalli**<sup>&#x2020;</sup>, M. Focchi, D. G. Caldwell and C. Semini
  <br> *IEEE Robotics and Automation Letters (RA-L), 2019*</td>
</tr>
</tbody>
</table>

<sup>*</sup> Equal authorship