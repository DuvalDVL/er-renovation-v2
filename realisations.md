---
layout: default
title: "Réalisations"
meta_title: "Réalisations : peinture, dégâts des eaux, débarras | ER Rénovation"
description: "Chantiers réalisés par ER Rénovation : peinture, remise en état après dégât des eaux, ratissage, déménagement et débarras en Haute-Savoie."
permalink: /realisations/
---
<section class="hero light plain">
  <div class="hero-t">
    <nav class="crumbs" aria-label="Fil d'Ariane"><ol><li><a href="{{ '/' | relative_url }}">Accueil</a></li><li aria-current="page">Réalisations</li></ol></nav>
    <h1 class="sm">Réalisations</h1>
    <p class="lead">Des chantiers récents en Haute-Savoie.</p>
  </div>
</section>
<section class="sec">
  <div class="wrap">
    <div class="gal">
      {%- for r in site.data.realisations %}
      <figure><div class="pic" style="--ar:4/3">{% include img.html name=r.name alt=r.alt ratio="4/3" sizes="(min-width:980px) 560px, 100vw" %}</div><figcaption>{{ r.alt }}</figcaption></figure>
      {%- endfor %}
    </div>
  </div>
</section>
{% include cta-band.html title="Votre <em>projet</em>" %}
