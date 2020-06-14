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
COMP 401: Project in Biology and Computer Science, McGill University, Montreal, QC, Canada, April 2020  
*Supervised by Ivan Kryukov & Simon Gravel*

**Regulation of Collective Endothelial Cell Migration by N-cadherin**  
BIOL 467: Independent Research Project 2, McGill University, Montreal, QC, Canada, April 2019  
*Supervised by Arnold Hayer*

**Investigating the Role of Classical Cadherin Isoforms in the Control of Collective Cell Migration**  
BIOL 466: Independent Research Project 1, McGill University, Montreal, QC, Canada, December 2018  
*Supervised by Arnold Hayer*
