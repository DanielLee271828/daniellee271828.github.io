---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
I submitted an article in
* Ma(𝛕ℏ)gazine, a Math magazine in CCCHWC (Topic: Development of Math in China)
* South China Morning Post Top 10

I also submitted an article in
* Acta Mathematica Sinica, English Series
* Chinese Physics Letters
* 工程数学学报

but do not get accepted.

I also write articles about Fluid Mechanics, Geophysics, Rotational Mechanics and Combinatorial Chemistry in school Science society newsletter - Sound of Science before.

An article about Fintech and Blockchain will be released.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
