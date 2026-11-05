---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<!-- To offer a PDF version, put it at files/cv.pdf and uncomment the next line -->
<!-- [Download PDF version]({{ base_path }}/files/cv.pdf){: .btn .btn--inverse} -->

Education
======
<!-- TODO: add years, e.g. "2025 – present" and "2020 – 2024" -->
* **M.Sc. in Applied Mathematics and Data Science** (in progress)  
  School of Applied Mathematics, Getulio Vargas Foundation (FGV EMAp), Rio de Janeiro
  * Research: normalised power priors and Bayesian dynamic borrowing
  * Advisor: Luiz Max Carvalho <!-- TODO: confirm -->
* **B.Sc. in Applied Mathematics**  
  School of Applied Mathematics, Getulio Vargas Foundation (FGV EMAp), Rio de Janeiro
  * Full scholarship from the Center for the Development of Mathematics and Sciences (CDMC)

Research experience
======
* **Research Assistant, hdbayes project**  
  Bayesian analysis of generalized linear models using historical data (R package [hdbayes](https://journal.r-project.org/articles/RJ-2026-010/)), in collaboration with the University of North Carolina at Chapel Hill
* **Research Assistant, Mosqlimate project**  
  Probabilistic forecasting of dengue and chikungunya across Brazilian states; submissions to the IMDC dengue forecasting sprint
* **Undergraduate research scholarships**: Scientific and Master's Initiation Program (PICME) and Institutional Program for Scientific Initiation Scholarships (PIBIC)

Publications
======
<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

Teaching
======
Teaching assistant at FGV EMAp:
<ul>{% for post in site.teaching reversed %}
  <li>{{ post.title | remove: " (TA)" }}, {{ post.type | downcase }}, {{ post.date | date: "%Y" }}</li>
{% endfor %}</ul>

Honors and awards
======
* Three-time medalist, Brazilian Public School Mathematics Olympiad (OBMEP)
* CDMC undergraduate scholarship, FGV EMAp

Skills
======
* **Programming:** R, Python, Stan, LaTeX, Git, command-line tools
* **Methods:** Bayesian inference and computation, power priors, generalized linear models, survival analysis, time-series forecasting (SARIMAX), spatio-temporal models (INLA)
* **Languages:** Portuguese (native), English
