---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>

![cover of Cripping Girlhood](https://press.umich.edu/var/site/storage/images/university-of-michigan-press/books/c/cripping-girlhood2/9780472076741_cover/4924170-1-eng-CA/9780472076741_cover1_rb_modalcover.jpg) 
Read an open access copy of *Cripping Girlhood* (University of Michigan, 2024) [here](https://doi.org/10.3998/mpub.12769443)
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
