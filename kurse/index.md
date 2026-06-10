---
layout: page
title: "Kurse und Workshops | GetPEC mbH"
description: "Intensivkurse und Workshops zu Wärmeübertragung und thermodynamischen Grundlagen – angeboten von GetPEC mbH mit Dozenten aus Wissenschaft und Industrie."
hero_title: "Kurse und Workshops"
hero_subtitle: "Fundiertes Fachwissen zu thermodynamischen und messtechnischen Themen – praxisnah vermittelt von erfahrenen Dozenten aus Wissenschaft und Industrie."
hero_image: "/assets/images/hero-courses.png"
permalink: /kurse/
---

<section class="section">
  <div class="container">
    <p class="lead">
      GetPEC bietet Intensivkurse zu thermodynamischen Grundlagen für Ingenieure und Naturwissenschaftler an. Die Kurse verbinden ein wissenschaftliches Fundament mit praktischer Anwendungsrelevanz.
    </p>

    {% for course in site.data.courses %}
    <div class="highlight-box" style="margin-top:2rem">
      <h2><a href="{{ course.url | relative_url }}" style="color:inherit;text-decoration:none">{{ course.title }}</a></h2>
      <p>{{ course.description }}</p>
      <ul style="list-style:none;padding:0;display:flex;flex-wrap:wrap;gap:1rem;margin:1rem 0">
        <li><strong>Termin:</strong> {{ course.date }}</li>
        <li><strong>Ort:</strong> {{ course.location }}</li>
        <li><strong>Format:</strong> {{ course.format }}</li>
        <li><strong>Dauer:</strong> {{ course.duration }}</li>
      </ul>
      <p>
        <strong>Präsenz:</strong> {{ course.price_presence }} &nbsp;|&nbsp;
        {{ course.price_note }}
      </p>
      <p>
        <a href="{{ course.url | relative_url }}" class="btn btn-primary">Zum Kurs</a>
        &nbsp;
        <a href="{{ '/anmeldung/' | relative_url }}" class="btn btn-outline">Jetzt anmelden</a>
      </p>
    </div>
    {% endfor %}

    <div class="info-box" style="margin-top:2rem">
      <p><strong>Weitere Kurse in Vorbereitung:</strong> GetPEC plant weitere Kursangebote zu Messtechnik, IR-Thermographie und spezifischen thermodynamischen Themen. Sprechen Sie uns an, wenn Sie Interesse an einem spezifischen Thema haben oder einen Inhouse-Workshop wünschen.</p>
    </div>

  </div>
</section>
