---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **PhD in plant biology**, Université Paris-Saclay, since September 2024
  * Doctoral school: Sciences du Végétal : du gène à l'écosystème
  * Thesis: *Editing of strigolactone biosynthesis genes in pea for the modulation of rhizospheric interactions and assessment of associated risks*
  * IJPB (INRAE, Versailles) and Plant Health Laboratory (ANSES)
  * Supervisors: Fabien Nogué, Alexandre de Saint Germain and Julie Mallet
* **Engineering degree**, Université de Technologie de Compiègne (UTC), from 2017
  * Exchange semester (6 months) at Technische Universität Braunschweig, Germany

Research experience
======
* **Research internship** (6 months), Institut Jean-Pierre Bourgin (IJPB), INRAE, Versailles
  * Cell-cycle regulation of Cas9 activity to improve homology-directed repair (HDR) in the moss *Physcomitrium patens*
  * Supervisors: Fabien Nogué and Pierre-François Perroud

* **Research internship** (6 months), 2020, ECOBIO lab, Rennes
  * Inhibition of sewage sludge anaerobic digestion by propionic acid
  * Supervisor: Céline Roose-Amsaleg
  * This work contributed to a [publication](https://doi.org/10.1016/j.jece.2026.123824) in the *Journal of Environmental Chemical Engineering*

Awards
======
* **Best talk award**, [2026 INRAE BAP division PhD and postdoc days](https://ijpb.versailles.inrae.fr/en/news/2026-inrae-bap-division-phd-and-postdoc-days-organised-by-the-ijpb), May 2026
  * For the talk *A novel gene editing protocol opens the door to strigolactone diversity studies in pea*

Publications
======
  <ul>{% assign sorted_publications = site.publications | sort: "order" %}{% for post in sorted_publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks reversed %}{% if post.type == "Talk" %}
    {% include archive-single-talk-cv.html  %}
  {% endif %}{% endfor %}</ul>

Posters
======
  <ul>{% for post in site.talks reversed %}{% if post.type == "Poster" %}
    {% include archive-single-talk-cv.html  %}
  {% endif %}{% endfor %}</ul>

Teaching and other activities
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

