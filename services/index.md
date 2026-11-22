---
layout: default
title: "Services"
meta_title: "Services : peinture, dégâts des eaux, débarras, enduits | ER Rénovation"
description: "Tous les services d'ER Rénovation à Passy : peinture, remise en état après dégât des eaux, ratissage, sols souples, déménagement et débarras."
permalink: /services/
---
<section class="hero light plain">
  <div class="hero-t">
    <nav class="crumbs" aria-label="Fil d'Ariane"><ol><li><a href="{{ '/' | relative_url }}">Accueil</a></li><li aria-current="page">Services</li></ol></nav>
    <h1 class="sm">Nos services</h1>
    <p class="lead">Ce que nous faisons, et ce que nous ne faisons pas : une offre resserrée sur les travaux où nous sommes les plus efficaces.</p>
  </div>
</section>
<section class="sec">
  <div class="wrap">
    <div class="idx">
      {%- for s in site.data.services %}
      <a class="row" href="{{ s.url | relative_url }}"><span class="nm">{{ s.name }}</span><span class="ds">{{ s.short }}</span></a>
      {%- endfor %}
      <a class="row" href="{{ '/agences-immobilieres-syndics/' | relative_url }}"><span class="nm">Agences et syndics</span><span class="ds">Remise en état de logements : fin de bail, vente, sinistre.</span></a>
    </div>
  </div>
</section>
{% include cta-band.html title="Parlons de votre <em>projet</em>" %}
