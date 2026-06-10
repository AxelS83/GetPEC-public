---
layout: page
title: "Leistungen | GetPEC mbH"
description: "GetPEC bietet thermodynamische Beratung, Prüfstandsentwicklung, Messtechnik, Wärmeübertragungsanalyse, Auftragsmessungen und IR-Thermographie für Forschung und Industrie."
hero_title: "Leistungen"
hero_subtitle: "Von der thermodynamischen Analyse bis zum vollautomatisierten Prüfstand – GetPEC deckt das vollständige Spektrum thermischer Engineering-Dienstleistungen ab."
hero_image: "/assets/images/hero-services.png"
permalink: /leistungen/
---

<section class="section">
  <div class="container">
    <p class="lead">
      GetPEC mbH unterstützt Forschungseinrichtungen und Industrieunternehmen bei anspruchsvollen thermischen Fragestellungen. Alle Leistungen werden auf Basis wissenschaftlicher Methodik und mit dem Anspruch auf praxisnahe, wirtschaftliche Lösungen erbracht.
    </p>
    <div class="services-grid">
      {% for service in site.data.services %}
        {% include service-card.html service=service %}
      {% endfor %}
    </div>
  </div>
</section>

<section class="section section--bg">
  <div class="container">
    <h2 class="section-title">Wie wir arbeiten</h2>
    <div class="core-areas-grid">
      <div class="core-area-card">
        <span class="core-area-icon" aria-hidden="true">1️⃣</span>
        <h3>Erstkontakt</h3>
        <p>Sie beschreiben Ihre technische Fragestellung. Wir klären gemeinsam, ob und wie GetPEC helfen kann.</p>
      </div>
      <div class="core-area-card">
        <span class="core-area-icon" aria-hidden="true">2️⃣</span>
        <h3>Angebot</h3>
        <p>Wir erarbeiten ein maßgeschneidertes Konzept und unterbreiten Ihnen ein transparentes Angebot.</p>
      </div>
      <div class="core-area-card">
        <span class="core-area-icon" aria-hidden="true">3️⃣</span>
        <h3>Umsetzung</h3>
        <p>Wir führen das Projekt durch – mit regelmäßiger Kommunikation und dokumentierten Ergebnissen.</p>
      </div>
    </div>
  </div>
</section>

<section class="section">
  <div class="container">
    <div class="cta-box">
      <h2>Ihr Projekt besprechen</h2>
      <p>Teilen Sie uns Ihre Fragestellung mit. Wir melden uns zeitnah und besprechen, wie GetPEC Sie unterstützen kann.</p>
      <a href="/kontakt/" class="btn btn-primary btn-large">Anfrage stellen</a>
    </div>
  </div>
</section>
