---
layout: default
title: "Thermische Messtechnik und thermodynamische Beratung | GetPEC mbH"
description: "GetPEC entwickelt kundenspezifische Prüfstände, thermische Messtechnik und thermodynamische Analysen für Forschung, Entwicklung und industrielle Spezialanwendungen."
hero_title: "Thermische Messtechnik, Prüfstandsentwicklung und thermodynamische Beratung"
hero_subtitle: "GetPEC unterstützt Industrie und Forschung bei anspruchsvollen thermischen Fragestellungen – von der Beratung und Berechnung über die Durchführung experimenteller Untersuchung bis zur kundenspezifischen Prüfstandsentwicklung."
hero_image: "/assets/images/hero-thermal-engineering.png"
hero_cta:
  - label: "Technische Fragestellung besprechen"
    url: "/kontakt/"
    primary: true
  - label: "Seminar: Grundlagen der Wärmeübertragung"
    url: "/kurse/grundlagen-waermeuebertragung/"
    primary: false
permalink: /
---

{% include hero.html %}

<!-- Positionierung -->
<section class="positioning-section">
  <div class="container">
    <h2 class="section-title">Wissenschaftliche Expertise trifft industrielle Praxis</h2>
    <p class="positioning-text">
      GetPEC mbH wurde 2016 aus dem Institut für Technische Thermodynamik der TU Darmstadt heraus gegründet. Wir verbinden tiefes thermodynamisches Fachwissen mit dem Anspruch, praxisnahe und wirtschaftliche Lösungen für reale Ingenieursaufgaben zu entwickeln. Unsere Arbeit reicht von der Durchführung von Messkampagnen über technische Beratung und Effiziensanalysen bis zum Aufbau vollautomatisierter Prüfstand.
    </p>
  </div>
</section>

<!-- Drei Kernbereiche -->
<section class="section section--bg">
  <div class="container">
    <h2 class="section-title">Unsere drei Kernbereiche</h2>
    <div class="core-areas-grid">
      <div class="core-area-card">
        <span class="core-area-icon" aria-hidden="true">🔄</span>
        <h3>Prozesse</h3>
        <p>Auslegung, Bewertung und Optimierung thermodynamischer Prozesse und Systemkomponenten – von Wärmeübertragern bis zu Energiesystemen.</p>
      </div>
      <div class="core-area-card">
        <span class="core-area-icon" aria-hidden="true">🔧</span>
        <h3>Entwicklung</h3>
        <p>Unterstützung bei der Bauteil- und Baugruppenenentwicklung: kundenspezifische Messtechnik, Prüfstände und experimentelle Validierung.</p>
      </div>
      <div class="core-area-card">
        <span class="core-area-icon" aria-hidden="true">💡</span>
        <h3>Consulting</h3>
        <p>Neutrale Expertengutachten, technische Beratung und Trainings für thermodynamische Fragestellungen in Industrie und Forschung.</p>
      </div>
    </div>
  </div>
</section>

<!-- Leistungsübersicht -->
<section class="section">
  <div class="container">
    <h2 class="section-title">Leistungen</h2>
    <p class="section-subtitle">Von der Beratung bis zum betriebsbereiten Prüfstand – GetPEC bietet das vollständige Spektrum thermischer Engineering-Dienstleistungen.</p>
    <div class="services-grid">
      {% for service in site.data.services %}
        {% include service-card.html service=service %}
      {% endfor %}
    </div>
    <div class="text-center mt-8">
      <a href="{{ '/leistungen/' | relative_url }}" class="btn btn-outline">Alle Leistungen im Überblick</a>
    </div>
  </div>
</section>

<!-- Projektbeispiele -->
<section class="section section--bg">
  <div class="container">
    <h2 class="section-title">Projektbeispiele</h2>
    <p class="section-subtitle">Ausgewählte Beispiele aus der Projektarbeit von GetPEC – kundenspezifische Entwicklungen, keine Standardprodukte.</p>
    <div class="projects-grid">
      {% for project in site.data.project_examples %}
        {% include project-card.html project=project %}
      {% endfor %}
    </div>
    <div class="text-center mt-8">
      <a href="{{ '/projektbeispiele/' | relative_url }}" class="btn btn-outline">Alle Projektbeispiele</a>
    </div>
  </div>
</section>

<!-- Branchen -->
<section class="section">
  <div class="container">
    <h2 class="section-title">Branchen und Anwendungsfelder</h2>
    <div class="branchen-grid">
      <div class="branche-item">Luft- und Raumfahrt</div>
      <div class="branche-item">Automotive / Mobility</div>
      <div class="branche-item">Energie und Wärme</div>
      <div class="branche-item">Chemie und Prozesse</div>
      <div class="branche-item">Healthcare</div>
      <div class="branche-item">Elektronik</div>
      <div class="branche-item">Industrielle F&amp;E</div>
      <div class="branche-item">Hochschulen</div>
    </div>
    <div class="text-center mt-8">
      <a href="{{ '/branchen/' | relative_url }}" class="btn btn-outline">Branchen und Anwendungen</a>
    </div>
  </div>
</section>

<!-- Seminar-Banner -->
<div class="seminar-banner">
  <div class="container">
    <div class="seminar-banner-inner">
      <div>
        <h2>Seminar: Grundlagen der Wärmeübertragung</h2>
        <p>16.–17. November 2026 &nbsp;|&nbsp; Darmstadt – Welcome Hotel &nbsp;|&nbsp; Präsenz 750 € zzgl. MwSt.</p>
        <p>In zwei Tagen vom Grundlagenwissen zur sicheren Anwendung – praxisnah verstehen, berechnen und anwenden.</p>
      </div>
      <div style="flex-shrink:0">
        <a href="{{ '/kurse/grundlagen-waermeuebertragung/' | relative_url }}" class="btn btn-primary">Zum Kurs</a>
        &nbsp;
        <a href="{{ '/anmeldung/' | relative_url }}" class="btn btn-secondary-outline">Jetzt anmelden</a>
      </div>
    </div>
  </div>
</div>

<!-- Referenzen -->
{% include customer-grid.html %}

<!-- Team -->
<section class="section">
  <div class="container">
    <h2 class="section-title">Das Team</h2>
    <p class="section-subtitle">GetPEC verbindet wissenschaftliche Exzellenz mit praktischer Ingenieursarbeit.</p>
    <div class="team-grid">
      {% for member in site.data.team %}
      <article class="team-card">
        <div class="team-card-image">
          <img src="{{ '/assets/images/' | append: member.image | relative_url }}"
               alt="{{ member.name }}"
               loading="lazy"
               width="480" height="360">
        </div>
        <div class="team-card-body">
          <h3 class="team-card-name">{{ member.name }}</h3>
          <p class="team-card-role">{{ member.role }}</p>
          <p class="team-card-role-detail">{{ member.role_detail }}</p>
        </div>
      </article>
      {% endfor %}
    </div>
    <div class="text-center mt-8">
      <a href="{{ '/team/' | relative_url }}" class="btn btn-outline">Team kennenlernen</a>
    </div>
  </div>
</section>

<!-- CTA Abschluss -->
<section class="section section--dark">
  <div class="container">
    <div class="cta-box">
      <h2>Haben Sie eine thermische Fragestellung?</h2>
      <p>Sprechen Sie uns an – wir analysieren Ihre Aufgabenstellung und machen Ihnen ein maßgeschneidertes Angebot.</p>
      <a href="{{ '/kontakt/' | relative_url }}" class="btn btn-primary btn-large">Kontakt aufnehmen</a>
      <a href="{{ '/leistungen/' | relative_url }}" class="btn btn-secondary-outline btn-large">Leistungen ansehen</a>
    </div>
  </div>
</section>
