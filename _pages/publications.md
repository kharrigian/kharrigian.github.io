---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

"Geocoding Without Geotags: A Text-based Approach for reddit." **Harrigian, K.** *In Proceedings of the 4th Workshop on Noisy User-generated Text (EMNLP)* [[Paper](http://aclweb.org/anthology/W18-6103)] [[Slides](./files/WNUT_Talk.pdf)]
{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
