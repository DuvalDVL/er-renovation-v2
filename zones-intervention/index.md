---
layout: default
title: "Zones d'intervention"
meta_title: "Zones d'intervention : Passy, Sallanches, Chamonix, Megève | ER Rénovation"
description: "ER Rénovation intervient à Passy, Sallanches, Saint-Gervais, Chamonix et Megève, et sur demande dans toute la Haute-Savoie."
permalink: /zones-intervention/
---
<section class="hero light plain">
  <div class="hero-t">
    <nav class="crumbs" aria-label="Fil d'Ariane"><ol><li><a href="{{ '/' | relative_url }}">Accueil</a></li><li aria-current="page">Zones d'intervention</li></ol></nav>
    <h1 class="sm">Où intervenons-nous ?</h1>
    <p class="lead">Autour de Passy, dans le Pays du Mont-Blanc, et plus loin en Haute-Savoie quand le chantier le justifie.</p>
  </div>
</section>
<section class="sec">
  <div class="wrap">
    <div class="idx">
      {%- for z in site.data.zones %}
      <a class="row" href="{{ z.url | relative_url }}"><span class="nm">Rénovation à {{ z.name }}</span><span class="ds">Peinture, dégâts des eaux, enduits, débarras et déménagement.</span></a>
      {%- endfor %}
    </div>
    <p style="margin-top:30px;max-width:44em">Pour un chantier plus éloigné en Haute-Savoie, jusqu'à Thonon, contactez-nous : nous étudions chaque demande selon le type de travaux et la durée du chantier.</p>
  </div>
</section>
{% include cta-band.html %}
