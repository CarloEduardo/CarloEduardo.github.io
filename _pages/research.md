---
layout: archive
title: "Investigación"
permalink: /research/
author_profile: true
header:
  og_image: "research/ecdf.png"
---

Mi investigación se centra en dos áreas principales: comprender cómo la geografía influye en el comportamiento de los actores antes, durante y después de los conflictos civiles, y desarrollar nuevas herramientas para mejorar el estudio de las instituciones (tanto formales como informales) en contextos de paz y conflicto. Una línea de investigación explora cómo los territorios habitados por distintos grupos étnicos influyen en la formación de grupos rebeldes y condicionan su relación con el Estado. Mi interés por la geografía también se refleja en proyectos sobre conflictos activos, como el análisis de los ataques contra fuerzas de paz de las Naciones Unidas por parte de grupos insurgentes, la victimización de la población civil tras la conquista territorial por grupos rebeldes y la violencia comunal en contextos de alta fragilidad.

Mi segunda línea de investigación se enfoca en el desarrollo de nuevas métricas para medir instituciones mediante métodos cuantitativos avanzados. Uno de estos proyectos utiliza modelos bayesianos de teoría de respuesta al ítem (Bayesian Item Response Theory) para estimar la solidez de los acuerdos de paz como una variable latente, evitando el sesgo de postratamiento que supone emplear la duración de los acuerdos como un indicador de su fortaleza. En otros trabajos, aplico técnicas de aprendizaje no supervisado a más de mil millones de registros de comercio internacional a nivel de producto para medir la interdependencia económica y el intercambio económico ilícito.

En una nueva línea de investigación, aprovecho datos provenientes de redes sociales para estudiar la participación en movimientos extremistas en distintos contextos, con el objetivo de comprender mejor las etapas tempranas del proceso de radicalización.

<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
