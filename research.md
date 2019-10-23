---
layout: page
permalink: /research/
pubs:

    - title:   "Perception of perspective distortions in image-based rendering"
      author:  "P. Vangorp, C. Richardt, EA Cooper, G. Chaurasia, MS Banks, G. Drettakis"
      journal: "ACM Transactions on Graphics"
      note:    "SIGGRAPH"
      year:    "2013"
      url:     "http://www-sop.inria.fr/reves/Basilic/2013/VRCCBD13/"
      doi:     "http://dx.doi.org/10.1145/2461912.2461971"
      image:   "http://www-sop.inria.fr/reves/Basilic/2013/VRCCBD13/experiment.png"
---
## Peer reviewed publications

{% assign thumbnail="right" %}

{% for pub in site.data.cv.publications %}
<!-- {% if pub.image %}
{% include image.html url=pub.image caption="" height="80px" align=thumbnail %}
{% endif %} -->
{{pub.author}}<br />
**{{pub.title}}**<br />
*{{pub.journal}}*
{% if pub.note %} *({{pub.note}})*
{% endif %} *{{pub.year}}*  [[web]({% if pub.internal %}{{pub.url | prepend: site.baseurl}}{% else %}{{pub.url}}{% endif %})] {% if pub.doi %}[[doi]({{pub.doi}})]{% endif %}

{% endfor %}

-----

## Doctoral thesis

**Algorithms & perceptual analysis for interactive free viewpoint image-based navigation** [[web]({{ "/research/thesis/" | prepend: site.baseurl}})]<br />
*Adviser: [George Drettakis](http://www-sop.inria.fr/members/George.Drettakis)* <br />
[INRIA](http://www.inria.fr/sophia), 2014




