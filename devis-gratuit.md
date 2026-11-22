---
layout: default
title: "Devis gratuit"
meta_title: "Devis gratuit | ER Rénovation, artisan à Passy"
description: "Demandez un devis gratuit à ER Rénovation, artisan à Passy : 06 88 48 34 03 ou formulaire en ligne. Peinture, dégâts des eaux, débarras, déménagement."
permalink: /devis-gratuit/
---
<section class="hero light plain">
  <div class="hero-t">
    <nav class="crumbs" aria-label="Fil d'Ariane"><ol><li><a href="{{ '/' | relative_url }}">Accueil</a></li><li aria-current="page">Devis gratuit</li></ol></nav>
    <h1 class="sm">Demandez votre devis gratuit</h1>
    <p class="lead">Décrivez votre projet : nous revenons vers vous rapidement.</p>
  </div>
</section>
<section class="sec quote-sec">
  <div class="wrap layout">
    <div>
      <h2>Nos coordonnées</h2>
      <p><strong>{{ site.data.site.name }}</strong><br>{{ site.data.site.street }}<br>{{ site.data.site.zip }} {{ site.data.site.city }}</p>
      <p>Téléphone : <a href="tel:{{ site.data.site.phone_e164 }}"><strong>{{ site.data.site.phone }}</strong></a></p>
      <p>E-mail : <a href="mailto:{{ site.data.site.email }}">{{ site.data.site.email }}</a></p>
      <p>{{ site.data.site.hours_label }}.</p>
      <p>Pour un devis plus rapide, joignez à votre message des photos du chantier ou de l'état du logement.</p>
    </div>
    {% include contact-form.html %}
  </div>
</section>
