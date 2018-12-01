---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

"Geocoding Without Geotags: A Text-based Approach for reddit." **Harrigian, K.** *In Proceedings of the 4th Workshop on Noisy User-generated Text (EMNLP)* [[<span style="color:blue">Paper</span>](http://aclweb.org/anthology/W18-6103)] [[<span style="color:blue">Slides</span>](https://kharrigian.github.io/files/WNUT_Talk.pdf)]
{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
