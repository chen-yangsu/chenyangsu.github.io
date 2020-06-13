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

## Technical Reports

**Inferring the History of Admixed Populations**
[(pdf)](http://chenyangsu.github.io/files/2020-04-17-comp401.pdf)  
Su, C.-Y., Kryukov, I., and Gravel, S., COMP 401: Project in Biology and Computer Science, McGill University, Montreal, QC, Canada, April 2020

**Regulation of Collective Endothelial Cell Migration by N-cadherin**
[(pdf)](http://chenyangsu.github.io/files/2019-04-13-biol467.pdf)  
Su, C.-Y. and Hayer, A., BIOL 467: Independent Research Project 2, McGill University, Montreal, QC, Canada, April 2019

**Investigating the Role of Classical Cadherin Isoforms in the Control of Collective Cell Migration**
[(pdf)](http://chenyangsu.github.io/files/2018-12-04-biol466.pdf)  
Su, C.-Y. and Hayer, A., BIOL 466: Independent Research Project 1, McGill University, Montreal, QC, Canada, December 2018
