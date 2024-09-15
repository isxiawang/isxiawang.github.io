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

<sup>*</sup> Equal authorship

<div class='paper-box'>
<div class='paper-box-image'>
<div>
<div class="badge">ICMR 2024</div>
<img src='images/paper_asrelvis_ICMR24.jpg' alt="sym" width="100%">
</div>
</div>
<div class='paper-box-text' markdown="1" >
**RE-IDVIS: Person Re-Identification System based on Interactive Visualization**

**<u>Wang Xia</u>**, Guodao Sun, Zihao Zhu, Pan Liang, Sujia Zhu, Yiming Wu, Haoran Liang, Ronghua Liang

Proceedings of the 2024 International Conference on Multimedia Retrieval (ICMR), 2024.

</div>
</div>  